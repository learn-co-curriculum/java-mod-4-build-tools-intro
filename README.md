# Build Tools Introduction

## Learning Goals

- Explain what a build tool does.

## Introduction

A Java project consists of the source code, test code, configurations,
libraries, dependencies, and task runners in a structured folder. A build tool helps
us to manage an entire project and create a workflow for generating easily
runnable applications.

## Features

Modern build tools can perform a wide variety of tasks that
developers need to do daily. Here are some of the things you might use a build
tool for:

1. Adding Dependencies: We can add dependencies to our project easily by using
   declarative definitions.
2. Compilation: We can define compilation criteria and commands to streamline
   the compilation process.
3. Packaging Compiled Code: Build processes can be defined to generate
   production-ready application archives like JAR.
4. Test Runners: We can create test workflows to automatically run tests based
   on certain criteria to avoid bugs after altering the code.
5. Easy Configuration: Modern tools generally have a lot of conventions to make
   it easier to start a project while also being highly configurable.
6. Cross Platform: Allows projects to be easily managed across different
   environments.

## Maven and Gradle

Maven and Gradle are two popular build automation tools. 

- Maven is based on developing Java projects. Gradle is based on developing
domain-specific language (DSL) projects and can build applications of any kind, including Java.
- Maven uses XML to structure a project. Gradle uses a DSL based on Groovy or Kotlin.  
- Gradle is faster than Maven in terms of project build and execution.
- Maven has been around much longer than Gradle and is currently the most popular build tool.

In the next lessons, we will step through the process of creating and
configuring a Maven project and a Gradle project.  This will allow
us to understand the similarities and differences between the two build tools.

## Conclusion

A build tool makes it easier to manage large projects by automating many tasks.
There are several build tools available, including Maven and Gradle.


## Resources

[Apache Maven Project](https://maven.apache.org/)  
[Gradle Build Tool](https://gradle.org/)  
