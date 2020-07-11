### Design: 2/3

- The node class seems to just wrap the functionalities already present in the default String class, so is it truly necessary?

- If you override equals(), you must override hashCode() as well, or else your definition of equality will not be consistent.

- Consider adding a containsEdge() method, or similar, to add additional functionalities to the user.

### Documentation & Specification (including JavaDoc): 3/3

- Constructors should not have an @spec.modifies tag on them, as nothing is being modified on the object level yet.

### Testing (test suite quality & implementation): 3/3

- Initialization of things in JUnit test should have a @Before tag on them.

### Code quality (code stubs/skeletons only, nothing else): 2/3

- Seems like a bit of generics was used on your LabeledEdge class with: "public static class LabeledEdge<Node>." Save this for HW5-pt2!

### Mechanics: 3/3

#### Overall Feedback

- Good design overall, just some small fixes to be made.

#### More Details

None.
