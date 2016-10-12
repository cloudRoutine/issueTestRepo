# Idea 8306538: Allow quotations of expressions used as Type Provider arguments #

### Status : open

### Submitted by thinkb4coding on 6/10/2015 12:00:00 AM

### 30 votes

This would enable scenarios where the type provider can rewrite, or abstract at compile time F# code and emit new one.
It could replace a macro system without the need for new syntax or tooling.


------------------------
## Comments


## Comment by thinkb4coding on 6/10/2015 4:20:00 AM
It could be used by transpilers to check validity and emit code at design/compile time


## Comment by Don Syme on 6/10/2015 7:16:00 AM
Hi @thinkb4coding
I would very much be in favour of this feature for F# vNext.
See also [/archive/suggestion-6023655-allow-passing-other-types-of-parameters-to-type-pr](/archive/suggestion-6023655-allow-passing-other-types-of-parameters-to-type-pr.md)


## Comment by Don Syme on 2/4/2016 2:08:00 PM
Just to note that this would almost certainly require this to have been fully implemented: [/archive/suggestion-5675977-allow-type-providers-to-generate-types-from-other](/archive/suggestion-5675977-allow-type-providers-to-generate-types-from-other.md)

