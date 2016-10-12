# Idea 12814485: Add units of measure for standard type aliases #

### Status : open

### Submitted by Friedrich von Never on 3/5/2016 12:00:00 AM

### 3 votes

Currently there is a support for `float<cm>`, but not `double<cm>`; I should call it `float32<cm>`. Almost in every other position `float` and `double` are completely equivalent (and some programmers prefer `double` over `float`). Shouldn't it be the case for units of measure support?
Also, it seems that units of measure are not supported for unsigned types at all. Was it a design decision? I suggest adding these.


------------------------
## Comments

