# Idea 12879717: Allow record inheritance / multiple "inheritance" #

### Status : open

### Submitted by Vasily Kirichenko on 3/10/2016 12:00:00 AM

### 17 votes

I propose to add multiple ***fields*** inheritance into records:
type Person =
{ First: string
Last: string }
type Foo = { Bar: int }
type Student =
inherit Person
inherit Foo
{ GPA: float }
let student = { First = "a"; Last = "b"; Bar = 2; GPA = 1.0 }
Making the same thing with composition results with not such an elegance flat records.
This approach is used, for example, in Nitra AST DSL, see https://github.com/rsdn/Nitra-Mini-C/blob/master/Nitra-Mini-C/MiniC-ast.nitra#L94


------------------------
## Comments

