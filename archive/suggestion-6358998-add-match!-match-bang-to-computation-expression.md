# Idea 6358998: Add match! (match-bang) to computation expressions #

### Status : declined

### Submitted by Nikon the Third on 8/28/2014 12:00:00 AM

### 1 votes

Often I come across code like this:
async {
let! value = readValueTask
match value with
| ...
| ...
}
where value has to be bound using let! and is only ever used in the following pattern match.
It would be nice to just write:
async {
match! readValueTask with
| ...
| ...
}



## Response 
### by fslang-admin on 9/6/2014 12:00:00 AM

Declining due to the conflict with the Joinads proposal., see comment below.
Don Syme, BDFL F# Language Evolution

------------------------
## Comments


## Comment by Don Syme on 9/3/2014 4:45:00 AM
The conflict with the proposed syntax for "joinads" seems like a problem here
See [/archive/suggestion-5663965-integrate-joinads-extension](/archive/suggestion-5663965-integrate-joinads-extension.md)


## Comment by Mark Seemann on 5/24/2016 12:51:00 AM
The joinads proposal is also closed, so could we reopen this one?

