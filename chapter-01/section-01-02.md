# Chapter 1 — Java Installation and First Program

## Section 1.2 — JDK, Compiler, Bytecode, and IDE

- **Section ID:** CH01-S02
- **Transcript:** 00:00:32–00:00:58
- **Audience:** Recent CSE graduate; no industry experience required
- **Questions and answers:** 6
- **Source:** Uploaded Java course transcript

### Context

A basic Java coding setup uses two things: a **Java Development Kit (JDK)** and an **Integrated Development Environment (IDE)**. The JDK includes a **compiler**, which converts Java **source code** (the written code) into **bytecode**, described as code that can run on a machine. The IDE is a workspace for writing code and is presented as more suitable for coding than a general-purpose editor such as Notepad.

The section distinguishes **where code is written** from **what compiles it**, then describes the compiled result. It does not explain JVM internals, terminal commands, installation procedures, or actual execution steps.

**Concept flow:** Java source code → JDK's compiler → bytecode. An IDE provides the workspace for writing the source.

### Sequenced Questions and Answers

**CH01-S02-Q01.** What two development components are introduced as needed to start coding with Java, and what is the primary role of each?

**Answer:** The **JDK** supplies development tools, including the compiler that processes Java code. The **IDE** supplies the workspace where the code is written.

**CH01-S02-Q02.** Which component inside the JDK processes a Java program, and what transformation does it perform?

**Answer:** The **compiler** converts written Java **source code** into **bytecode**.

**CH01-S02-Q03.** Differentiate Java source code from bytecode by explaining how each is obtained in the described workflow.

**Answer:** **Source code** is the Java code written by a developer. **Bytecode** is the output created when the compiler compiles that source code. The section describes bytecode as code that can run on a machine.

**CH01-S02-Q04.** Why introduce an IDE when source code can also be typed in a general-purpose editor such as Notepad?

**Answer:** An **IDE** is a dedicated coding workspace. It is presented as more suitable for writing programs because an ordinary text editor such as Notepad may not be sufficient or convenient for the coding workflow.

**CH01-S02-Q05.** A graduate creates a Java source file in an IDE and concludes that bytecode must already exist. What step is missing from this reasoning?

**Answer:** **Compilation** has not been established. Writing or opening source code in an IDE is different from the compiler **transforming that source into bytecode**.

**CH01-S02-Q06.** A teammate describes the process as “the IDE converts bytecode into source code, and the JDK is just the editor.” Reconstruct the correct workflow and component responsibilities.

**Answer:** The **IDE** is the workspace for writing **Java source code**. The **JDK includes the compiler**, which converts **source code into bytecode**—not the other way around. The section describes the resulting bytecode as runnable on a machine; it does not cover execution internals.

### Source boundary

Only the responsibilities of the JDK, compiler, IDE, source code, and bytecode are established here. Installation, JVM details, and practical commands belong to later material.
