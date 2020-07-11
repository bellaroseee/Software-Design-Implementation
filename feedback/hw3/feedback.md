### Code quality score: 3/3

### Mechanics: 3/3

#### General Feedback

Good work!

#### Specific Feedback

##### RandomHello

When selecting a greeting in `RandomHello`, the best style would use the length
of the array to specify the maximum value for the random integer generation:
```
String nextGreeting = greetings[rand.nextInt(greetings.length)];
```
Notice how this benefits us later on if we wanted to change the number of
possible greetings in the array.

##### BallContainer

Your BallContainer add/remove methods are more complicated than they need to be.
Look at the documentation for `Set.add` and `Set.remove` and see whether you
need to explicitly use `contains` to check for existence.

Your BallContainer contains methods is more complicated than it needs to be
since it already returns a boolean.

##### Box

Remember to follow naming conventions for classes. Class names should be
PascalCase/UpperCamelCase.
