### Answers Score: --/10
- Problem 1: -/7
- Problem 4: -/3

### Design: 3/3

### Documentation & Specification (including JavaDoc): 2/3

### Code quality (code and internal comments including RI/AF): 3/3

### Testing (test suite quality & implementation): 3/3

### Mechanics: 3/3

#### Overall Feedback

- good coverage of testing
- detailed documentation
- overall, great job :)

#### More Details

`@spec.requires` And `@throws`
Specifying both `@spec.requires !A` and `@throws SampleException when A` is
contradictory, since, on the one hand, you are declaring the behavior of the
method under the condition `A` to be undefined, and, on the other, you are
declaring it to be defined (to throw an exception) under the condition `A`.

inexpensive check can be outside of your `if(CHECK_REP)` in your `checkRep`
