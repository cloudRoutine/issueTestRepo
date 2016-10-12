# Idea 14533251: Make "ModuleSuffix" the default if a type has the same name #

### Status : completed

### Submitted by Onur on 6/2/2016 12:00:00 AM

### 13 votes

[<CompilationRepresentation(CompilationRepresentationFlags.ModuleSuffix )>]
This attribute is so commonly used on top of modules. But it is a bit verbose and tedious. I suggest offer an alternative shortcut like [<ModuleSuffix>] or achieve the same effect by a compiler switch.
Update: the proposal has been adjusted to say that ModuleSuffix is implied if a type and a module have the same name within the same namespace declaration group



## Response 
### by fslang-admin on 8/2/2016 12:00:00 AM

This has been completed, see RFC at https://github.com/fsharp/FSharpLangDesign/blob/master/RFCs/FS-1019-implicitly-add-the-module-suffix.md

------------------------
## Comments


## Comment by trek42 on 6/2/2016 4:22:00 PM
agreed, actually modulesuffix should have been the default setting IMO...but it's not feasible to change the default.

