# Idea 13361034: Implement implicit casts for yield #

### Status : open

### Submitted by Francois Brodeur on 4/8/2016 12:00:00 AM

### 4 votes

As described here: https://github.com/fsharp/fsharp/issues/545#event-620769998


------------------------
## Comments


## Comment by Gauthier Segay on 4/10/2016 8:38:00 PM
It seems there are other areas where this could also take place?
It is a bit annoying to have to explicitly cast but at least it is consistent wherever expected type is not an exact match.
Introducing this for yield only would create a special case.

