# Idea 10701768: Add stable sort for Array module #

### Status : declined

### Submitted by ふぇ～はぇ～ on 11/14/2015 12:00:00 AM

### 1 votes

Seq.sort and List.sort are based on Microsoft.FSharp.Primitives.Basics.Array.stableSortInPlace, so there are stable sort. But Array.sort is unstable. This is confusing.
Please be public the function Array.stableSortInPlace, etc.



## Response 
### by fslang-admin on 2/3/2016 12:00:00 AM

Declined: This is really a .NET thing

------------------------
## Comments


## Comment by Don Syme on 2/3/2016 2:27:00 PM
This really depends on .NET providing an efficient stable sort for arrays. It doesn't. Searching for "stable sort array c#" gives useful guides about what to do.

