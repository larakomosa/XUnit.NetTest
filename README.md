# XUnit.NetTest

#### Getting Project Setup 
- Once XUnit project is created, right click and reference the project you want to test.
- Install additional packages (xunit, xunit.runner.console. xunit.runner.visualstudio)

#### Layout of Test
- Arrange - values setup for test
- Act - action that we are testing
- Assert - This is what I expect, here is the actual value.  Let's test to see if they are the same.

#### Running Test
- Build file, run unit test.  Test should be written and test failed to ensure it works correctly.   
- Write the test before writing the code.

#### Differences between Fact and Theory
While facts are used to test invariant conditions, theories are tests that are true for a particular set of data passed as argument to the method. You would typically use the [Fact] attribute to write unit tests that have no method arguments
