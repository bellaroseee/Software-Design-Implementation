### Command line application: 2/3

### Design: 3/3

### Documentation & Specification (including JavaDoc): 3/3

### Code quality (code and internal comments including RI/AF when appropriate): 3/3

### Testing (test suite quality & implementation): 2/3

### Mechanics: 3/3

### Command line application extra credit:  -/3

#### Overall Feedback

Minor issues in testing, but otherwise well done.

#### More Details

For user interfaces in general, it is important to make sure all error cases are
handled in a graceful, user-friendly manner.  You cannot expect a user to read
an exception name or a stack trace and understand what's happening.

Script tests need comments.

Your test suite is lacking in coverage.  Here's a few ideas for interesting test
cases:
- Empty data file.
- Loading two graphs.
- Operations that mix graph loading and building.
- Cyclic graphs with path finding.
- Lexicographically least paths.
