### Code Quality Score: 2/3

### Mechanics: 3/3

#### Overall Feedback
Overall, good work.
#### More Details
RatTerm.java:
In your first constructor, notice that you can factor out the line "coeff = c" from the if-else statements.

RatPoly.java:
Missing loop invariants on non-trivial loops.
Using checkRep() in all public RatPoly methods would be better. This helps
find representation exposure and accidental mutation bugs earlier rather than
later.