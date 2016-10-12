# Idea 11661270: extend ComputationExpression builders with Map : m<'a> * ('a -> 'b) -> m<'b> #

### Status : open

### Submitted by Georg Haaser on 1/31/2016 12:00:00 AM

### 8 votes

In many scenarios computation expressions could be executed way more efficiently when having just a little more information.
The typical use-case for that would be something like
async {
let! a = something
return 2*a
}
which currently gets translated to:
async.Bind(something, fun a -> async.Return(2*a))
By monad laws (borrowed from haskell here) this must be equal to:
async.Map(something, fun a -> 2*a)
In many scenarios the latter can be implemented with a lot less overhead, so in my opinion it would be profitable to allow users to provide this "shortcut".


------------------------
## Comments

