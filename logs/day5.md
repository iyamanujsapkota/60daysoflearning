### TESTING TYPES : 

----

### Functional Testing
Functional testing verifies that each function of the software application operates in conformance with the requirement specification. This type of testing mainly involves black-box testing and is concerned with the functional requirements of an application.

**Key Points:**
- Validates the actions and operations of an application.
- Includes tests such as unit testing, integration testing, system testing, and acceptance testing.
- Ensures that the software behaves as expected.
- Examples include testing user interactions, APIs, databases, security, client/server applications, etc.

### Non-functional Testing
Non-functional testing checks the non-functional aspects of an application, such as performance, usability, reliability, etc. It focuses on how the system performs rather than the specific behaviors.

**Key Points:**
- Ensures that the software meets non-functional requirements.
- Includes performance testing, load testing, stress testing, scalability testing, security testing, etc.
- Assesses factors like speed, scalability, stability, and reliability.
- Examples include testing how many users can simultaneously use the application, how the system performs under heavy load, etc.

### Regression Testing
Regression testing involves re-running functional and non-functional tests to ensure that previously developed and tested software still performs correctly after a change. It aims to catch any defects introduced by changes.

**Key Points:**
- Ensures new changes do not adversely affect existing functionalities.
- Typically performed after code modifications, enhancements, or bug fixes.
- Can be automated to save time and effort.
- Examples include re-testing login functionality after a new feature is added or verifying the output of an application after a security patch.

### Smoke Testing
Smoke testing is a subset of acceptance testing and is often called "Build Verification Testing." It ensures that the most critical functions of an application work, but does not delve into finer details.

**Key Points:**
- Acts as a preliminary test to catch major issues early.
- Performed on initial builds of the software.
- Often automated to quickly validate new builds.
- Examples include verifying that the application launches successfully, basic navigation works, and critical functions are operational.

### Sanity Testing
Sanity testing is a subset of regression testing and focuses on verifying specific functionalities after changes. It checks whether a particular section of the application is still working after minor changes.

**Key Points:**
- Ensures that recent changes or fixes work correctly.
- Performed after receiving a new build to determine if it’s stable enough for further testing.
- Less exhaustive and more focused than regression testing.
- Examples include verifying that a new search feature works correctly or that a new bug fix does not break the related module.

### Summary
1. **Functional Testing:** Validates specific functions against requirements.
2. **Non-functional Testing:** Evaluates performance, usability, and other non-functional aspects.
3. **Regression Testing:** Ensures changes do not affect existing functionalities.
4. **Smoke Testing:** Quick checks on critical functions of a new build.
5. **Sanity Testing:** Focused checks on specific areas after minor changes.
