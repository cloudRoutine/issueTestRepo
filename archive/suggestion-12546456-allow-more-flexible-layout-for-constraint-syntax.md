# Idea 12546456: Allow more flexible layout for constraint syntax #

### Status : open

### Submitted by George on 3/1/2016 12:00:00 AM

### 1 votes

The following layout of constraints for a sample class should be possible.
GroupedFixtures<'A, 'B
when
'A :> Remote.RemoteWebDriver and
'A : (new: unit -> 'A) and
'B :> ServerFixture
>() as this =
Presently it almost was but the `new()` constraint use of parenthesis caused problems. currently all the constraints layout forces them on the same line which is not as clear or convenient (note the text, that `>() as this`, is allowed on a separate line):
GroupedFixtures<'A, 'B when 'A :> Remote.RemoteWebDriver and 'A : (new: unit -> 'A) and 'B :> ServerFixture
>() as this =


------------------------
## Comments

