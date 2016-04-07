# Clean Code - A Handbook of Agile Software Craftsmanship

# Chapter 1: Clean Code

## 1.1 There Will Be Code
* Code is really the language in which we ultimately express the requirements

## 1.2 Bad Code
* *Bad code brought the company down*
* *Later equals never*

## 1.3 The Total Cost of Owning a Mess
  * The Grand Redesign in the Sky
  * Attitude
  * The Primal Conundrum
  * The ARt of Clean Code?
  * What Is Clean Code?

## 1.4 Schools of Thought

## 1.5 We Are Authors

## 1.6 The Boy Scout Rule

## 1.7 Prequel and Principles

## 1.8 Conclusion

## 1.9 Bibliography

# Chapter 2: Meaningful Names

## 2.1 Introduction

## 2.2 Use Intention-Revealing Names

## 2.3 Avoid Disinformation

## 2.4 Make Meaningful Distinctions

## 2.5 Use Pronounceable Names

## 2.6 Use Searchable Names

## 2.7 Avoid Encodings
  * Hungarian Notation
  * Member Prefixes
  * Interfaces and Implementations

## 2.8 Avoid Mental Mapping

## 2.9 Class Names

## 2.10 Method Names

## 2.11 Don't Be Cute

## 2.12 Pick One Word per Concept

## 2.13 Don't Pun

## 2.14 Use Solution Domain Names

## 2.15 Use Problem Domain Names

## 2.16 Add Meaningful Context

## 2.17 Don't Add Gratuitous Context

## 2.18 Final Words

# Chapter 3: Functions

## 3.1 Small!
  * Blocks and Indenting

## 3.2 Do One Thing
  * Sections within Functions

## 3.3 One Level of Abstraction per Function
  * Reading Code from Top to Bottom: *The Stepdown Rule*

## 3.4 Switch Statements

## 3.5 Use Descriptive Names

## 3.6 Function Arguments
  * Common Monadic Forms
  * Flag Arguments
  * Dyadic Functions
  * Triads
  * Argument Objects
  * Argument Lists
  * Verbs and Keywords

## 3.7 Have No Side Effects
  * Output Arguments

## 3.8 Command Query Separation

## 3.9 Prefer Exceptions to Returning Error Codes
  * Extract Try/Catch Blocks
  * Error Handling Is One Thing
  * The `Error.java` Dependency Magnet

## 3.10 Don't Repeat Yourself

## 3.11 Structured Programming

## 3.12 How Do You Write Functions Like This?

## 3.13 Conclusion

## 3.14 SetupTeardownIncluder

## 3.15 Bibliography

# Chapter 4: Comments

## 4.1 Comments Do Not Make Up for Bad Code

## 4.2 Explain Yourself in Code

## 4.3 Good Comments
  * Legal Comments
  * Informative Comments
  * Explanation of Intent
  * Clarification
  * Warning of Consequences
  * TODO Comments
  * Amplification
  * Javadocs in Public APIs

## 4.4 Bad Comments
  * Mumbling
  * Reduntdant Comments
  * Misleading Comments
  * Mandated Comments
  * Journal Comments
  * Noise Comments
  * Scary Noise
  * Don't Use a Comment When You can Use a Function or a Variable
  * Position Markers
  * Closing Brace Comments
  * Attributions and Bylines
  * Commented-Out Code
  * HTML Comments
  * Nonlocal Information
  * Too Much Information
  * Inobvious Connection
  * Function Headers
  * Javadocs in Nonpublic Code
  * Example

## 4.5 Bibliography

# Chapter 5: Formatting

## 5.1 The Purpose of Formatting

## 5.2 Vertical Formatting
  * The Newspaper Metaphor
  * Vertical Openness Between Concepts
  * Vertical Density
  * Vertical Distance
  * Vertical Ordering

## 5.3 Horizontal Formatting
  * Horizontal Openness and Density
  * Horizontal Alignment
  * Indentation
  * Dummy Scopes

## 5.4 Team Rules

## 5.5 Uncle Bob's Formatting Rules

# Chapter 6: Objects and Data Structures

## 6.1 Data Abstraction

## 6.2 Data/Object Anti-Symetric

## 6.3 The Law of Demeter
  * Train Wrecks
  * Hybrids
  * Hiding Structure

## 6.4 Data Transfer Objects
  * Active Record

## 6.5 Conclusion

## 6.6 Bibliography

# Chapter 7: Error Handling

## 7.1 Use Exceptions Rather Than Return Codes

## 7.2 Write Your Try-Catch-Finally Statement First

## 7.3 Use Unchecked Exceptions

## 7.4 Provide Context with Exceptions

## 7.5 Define Exception Classes in Terms of a Caller's Needs

## 7.6 Define the Normal Flow

## 7.7 Don't Return Null

## 7.8 Don't Pass Null

## 7.9 Conclusion

## 7.10 Bibliography

# Chapter 8: Boundaries

## 8.1 Using Third-Party Code

## 8.2 Exploring and Learning Boundaries

## 8.3 Learning log4j

## 8.4 Learning Tests Are Better Then Free

## 8.5 Using Code That Does Not Yet Exist

## 8.6 Clean Boundaries

## 8.7 Bibliography

# Chapter 9: Unit Tests

## 9.1 The Thre Laws of TDD

## 9.2 Keeping Tests Clean
  * Tests Enable the -ilities

## 9.3 Clean Tests
  * Domain-Specific Testing Language
  * A Dual Standard

## 9.4 One Assert per Test
  * Sing Concept per Test

## 9.5 F.I.R.S.T

## 9.6 Conclusion

## 9.7 Bibliography

# Chapter 10: Classes

## 10.1 Class Organization
  * Encapsulation

## 10.2 Classes Should Be Small!
  * The Single Responsibility Principle
  * Cohesion
  * Maintaining Cohesion Results in Many Small Classes

## 10.3 Organizing for Change
  * Isolating from Change

## 10.4 Bibliography

# Chapter 11: Systems

## 11.1 How Would You Build a City?

## 11.2 Separate Constructing a System from Using It
  * Separation of Main
  * Factories
  * Dependency Injection

## 11.3 Scaling Up
  * Cross-Cutting Concerns

## 11.4 Java Proxies

## 11.5 Pure Java AOP Frameworks

## 11.6 AspectJ Aspects

## 11.7 Test Drive they System Architecture

## 11.8 Optimize Decision Making

## 11.9 Use Standards Wisely, When THey Add *Demonstrable* Value

## 11.10 Systems Need Domain-Specific Languages

## 11.11 Conclusion

## 11.12 Bibliography

# Chapter 12: Emergence

## 12.1 Getting Clean via Emergent Design

## 12.2 Simple Design Rule 1: Runs All the Tests

## 12.3 Simple Design Rules 2-4: Refactoring

## 12.4 No Duplication

## 12.5 Expressive

## 12.6 Minimal Classes and Methods

## 12.7 Conclusion

## 12.8 Bibliography

# Chapter 13: Concurrency

## 13.1 Why Concurrency?
  * Myths and Misconceptions

## 13.2 Challenges

## 13.3 Concurrency Defense Principles
  * Single Responsibility Principle
  * Corollary: Limit the Scope of Data
  * Corollary: Use Copies of Data
  * Corollary: Threads SHould Be as Independent as Possible

## 13.4 Know Your Library
  * Thread-Safe Collections

## 13.5 Know Your Execution Models
  * Producer-Consumer
  * Readers-Writers
  * Dining Philosophers

## 13.6 Beware Dependencies Between Sysnchronized Methods

## 13.7 Keep Synchronized Sections Small

## 13.8 Writing Correct Shut-Down Code Is Hard

## 13.9 Testing Threaded Code
  * Treat Spurious Failures as Candidate Threading Issues
  * Get Your Nonthreaded Code Working First
  * Make Your Threaded Code Pluggable
  * Make Your Threaded Code Tunable
  * Run with More Threads Than Processors
  * Run on Different Platforms
  * Intrument Your Code to Try and Force Failures
  * Hand-Coded
  * Automated

## 13.10 Conclusion

## 13.11 Bibliography

# Chapter 14: Successive Refinement

## 14.1 Args Implementation
  * How Did I Do This?

## 14.2 Args: The Rough Draft
  * So I Stopped
  * On Incrementalism

## 14.3 String Arguments

## 14.4 Conclusion

# Chapter 15: JUnit Internals

## 15.1 The JUnit Framework

## 15.2 Conclusion

# Chapter 16: Refactoring SerialDate

## 16.1 First, Make It Work

## 16.2 Then Make It Right

## 16.3 Conclusion

## 16.4 Bibliography

# Chapter 17: Smells and Heuristics

## 17.1 Comments
  * C1: *Inappropriate Information*
  * C2: *Obsolete Comment*
  * C3: *Redundant Comment*
  * C4: *Poorly Written Comment*
  * C5: *Commented-Out Code*

## 17.2 Environment
  * E1: *Build Requires More Than One Step*
  * E2: *Tests Requires More Then One Step*

## 17.3 Functions
  * F1: *Too Many Arguments*
  * F2: *Output Arguments*
  * F3: *Flag Arguments*
  * F4: *Dead Function*

## 17.4 General
  * G1: *Multiple Languages in One Source File*
  * G2: *Obvious Behavior Is Unimplemented*
  * G3: *Incorrect Behavior at the Boundaries*
  * G4: *Overridden Safeties*
  * G5: *Duplication*
  * G6: *Code at Wrong Level of Abstraction*
  * G7: *Base Classes Depending on THeir Derivatives*
  * G8: *Too Munch Information*
  * G9: *Dead Code*
  * G10: *Vertical Separation*
  * G11: *Inconsistency*
  * G12: *Clutter*
  * G13: *Artificial Coupling*
  * G14: *Feature Envy*
  * G15: *Selector Arguments*
  * G16: *Obscured Intent*
  * G17: *Misplaced Responsibility*
  * G18: *Inappropriate Static*
  * G19: *Use Explanatory Variables*
  * G20: *Function Names Should Say What They Do*
  * G21: *Understand the Algorithm*
  * G22: *Make Logical Dependencies Physical*
  * G23: *Prefer Polymorphism to If/Else or Switch/Case
  * G24: *Follow Standard Conventions*
  * G25: *Replace Magic Numbers with Named Constants*
  * G26: *Be Precise*
  * G27: *Structure over Convention*
  * G28: *Encapsulate Conditionals*
  * G29: *Avoid Negative Conditionals*
  * G30: *Functions Should Do One Thing*
  * G31: *Hidden Temporal Couplings*
  * G32: *Don't Be Arbitrary*
  * G33: *Encapsulate Boundary Conditions*
  * G34: *Functions Should Descend Only*
  * *One Level of Abstraction*
  * G35: *Keep Configurable Data at High Levels*
  * G36: *Avoid Transitive Navigation*

## 17.5 Java
  * J1: *Avoid Long Import Lists by Using Wildcards*
  * J2: *Don't Inherit Constants*
  * J3: *Constants versus Enums*

## 17.6 Names
  * N1: *Choose Descriptive Names*
  * N2: *Choose Names at the Appropriate Level of Abstraction*
  * N3: *Use Standard Nomemclature Where Possible*
  * N4: *Unambiguous Names*
  * N5: *Use Long Names for Long Scopes*
  * N6: *Avoid Endcodings*
  * N7: *Names Should Describe Side-Effects*

## 17.7 Tests
  * T1: *Insufficient Tests*
  * T2: *Use a Coverage Tool!*
  * T3: *Don't Skip Trivial Tests*
  * T4: *An Ignored Test Is a Question about an Ambiguity*
  * T5: *Test Boundary Conditions*
  * T6: *Exhaustively Test Near Bugs*
  * T7: *Patterns of Failure Are Revealing*
  * T8: *Test Coverage Patterns Can Be Revealing*
  * T9: *Tests Should Be Fast*

## 17.8 Conclusion

## 17.9 Bibliography

# Appendix A: Concurrency II

## 18.1 Client/Server Example
  * The Server
  * Adding Threading
  * Server Observations
  * Conclusion

## 18.2 Possible Paths of Execution
  * Number of Paths
  * Digging Deeper
  * Conclusion

## 18.3 Knowing Your Library
  * Executor Framework
  * Nonblocking Solution
  * Nonthread-Safe Classes

## 18.4 Depedencies Between Methods Can Break Concurrent Code
  * Tolerate the Failure
  * Client-Based Locking
  * Server-Based Locking

## 18.5 Increasing Throughput
  * Single-Thead Calculation of Throughput
  * Multithread Calculation of Throughput

## 18.6 Deadlock
  * Mutual Exclusion
  * Lock & Wait
  * No Preemption
  * Circular Wait
  * Breaking Mutual Exclusion
  * Breaking Lock & Wait
  * Breaking Preemption
  * Breaking Circular Wait

## 18.7 Testing Multithreaded Code

## 18.8 Tool Support for Testing Thread-Based Code

## 18.9 Conclusion

## 18.10 Tutorial: Full Code Examples
  * Client/Server Nonthreaded
  * Client/Server Using Threads

# Appendix B: org.jfree.date.SerialDate

# Appendix C: Cross References of Heuristics

# Epilogue

