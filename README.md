## What are the pros and cons of TDD?

### Pros

Some of the advantages of test driven development include the main points such as a reduceed amount of bugs or unintended functionalites, but more side effects include:

- a more flexible code base which can be easily refactored and extendeded
- The tests themselves can be used as a form of documentation for the code base, and can be used to help new developers understand the code base.
- The tests can also be used as a form of regression testing, to ensure that new changes to the code base do not break existing functionality.

### Cons

Analogously to the pros, a main disadvantage of test driven development is the extra time required to write both the test and the actual code. Other less obiovus disadvantages include:

- Writing inaccurate test cases can lead to false positves which can be difficult to debug.
- Test cases aimed at providing full code covereage can be introduce a lot of redundancy and can be difficult to maintain.
- Very complex or specific code such as time dependant, network dependant or any dependant code where its difficult to mock the dependancies can be difficult to test.

## Project Unit Tests

The following is a link to the implemented React Jest unit tests for the project:

`https://github.com/ECE444-2023Fall/project-1-web-application-design-group1-flask-and-furious/blob/mapbox_unittest/__tests__/mapBox.test.tsx`
