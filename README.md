# Hello, world!

This example project is written in Java, and tested with Gradle/JUnit.

### Objectives
- Familiarize yourself with the process of running the autograding tests and submitting PRs via GitHub Classroom and your Java IDE

### The assignment

- The tests are currently failing because of an output mismatch.
- Run the test suite and make sure that it succeeds.
  - Fixing the `System.out.println` in the main method will make the tests green.
- To submit your solution, create a pull request via GitHub IDE Integration or [via the command line](https://www.notion.so/strategio-technologists/Pull-Request-Instructions-aafde9fe4f6842e5af7177f99e608b5d). 
  - GitHub actions will run unit tests and _should_ only allow PRs and merging.

### Running this locally

Running this locally requires a JDK and Gradle.

Once everything is installed:

```bash
gradle build
```

### Run command

```bash
gradle test
```
