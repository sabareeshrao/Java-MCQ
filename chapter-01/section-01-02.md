# Chapter 1 — Java Installation and First Program

## Section 1.2 — JDK, Compiler, Bytecode, and IDE

- **Section ID:** CH01-S02
- **Transcript:** 00:00:32–00:00:58
- **Questions:** 15 (5 Easy, 5 Medium, 5 Hard)
- **Audience:** CSE graduate with no industry experience
- **Source:** Uploaded Java course transcript
- **Status:** Complete

### Context

A basic Java development setup introduces two essential components: the **Java Development Kit (JDK)** and an **Integrated Development Environment (IDE)**.

The JDK contains a compiler that converts Java source code—the code written by a developer—into bytecode. Bytecode is described as the resulting form of code that can run on a machine.

The IDE provides a workspace for writing code. It serves a different purpose from the compiler and provides a more suitable coding environment than relying on a basic text editor such as Notepad.

**Concept flow:** Java source code (written in a coding workspace such as an IDE) → compiler (contained in the JDK) → bytecode (described as runnable on a machine).

**Scope:** This section establishes the initial tool responsibilities and compilation concept. It does not demonstrate installation, command-line compilation, JVM internals, or program execution.

### Easy Questions (5)

1. **CH01-S02-E01:** Distinguish the purpose of a Java Development Kit from that of an Integrated Development Environment in a basic Java setup.
2. **CH01-S02-E02:** In Java compilation, what type of code is given to the compiler, and what type of code does it produce?
3. **CH01-S02-E03:** What is the relationship between the JDK and the Java compiler? Explain which one contains the other.
4. **CH01-S02-E04:** Where does bytecode fit between writing Java source code and running a program on a machine?
5. **CH01-S02-E05:** Why is a dedicated coding workspace useful when a developer could also write source code in a general-purpose text editor such as Notepad?

### Medium Questions (5)

1. **CH01-S02-M01:** Explain the complete flow from writing Java source code to obtaining bytecode. Identify the responsibility of each component involved.
2. **CH01-S02-M02:** A Java developer has written a program inside an IDE and assumes that writing the code means compilation is already complete. What is incorrect about this assumption?
3. **CH01-S02-M03:** A graduate has a JDK and Notepad but no IDE. Which part of the Java compilation process is available, and what benefit of the recommended development setup is missing?
4. **CH01-S02-M04:** A project setup document lists JDK, IDE, compiler, and bytecode as four separate software applications that must be downloaded. Identify the classification errors.
5. **CH01-S02-M05:** A colleague describes the JDK as the workspace for writing Java code and the IDE as the tool responsible for producing bytecode. How should these responsibilities be corrected?

### Hard Questions (5)

1. **CH01-S02-H01:** During a technical discussion, a candidate describes the following process:

   `Bytecode → Compiler → Java Source Code → Machine Execution`

   Identify the incorrect sequence and reconstruct the compilation flow using the concepts introduced in this section.

2. **CH01-S02-H02:** Two developers disagree about Java development tools. One claims that installing an IDE makes the JDK unnecessary. The other claims that the JDK and IDE have different responsibilities. Evaluate both claims and explain the technical distinction.

3. **CH01-S02-H03:** Two CSE graduates are configuring their computers. Developer A has installed only an IDE, while Developer B has obtained only a JDK. Evaluate both setups against the two-component development environment described here. Identify what each setup is missing.

4. **CH01-S02-H04:** A project onboarding document claims that opening a Java source file in an IDE automatically proves the program has been compiled into bytecode. Explain why this conclusion is not justified by the compilation process described in this section.

5. **CH01-S02-H05:** You are preparing a short technical onboarding explanation for a new Java developer. Construct a logically ordered explanation that covers the purpose of the IDE, the role of the JDK, the function of its compiler, and the resulting bytecode—without relying on installation commands or advanced Java runtime concepts.

### Duplicate-control policy

- Stable question IDs: `CH01-S02-[EMH]01` through `CH01-S02-[EMH]05`.
- Check both exact wording and question meaning against all existing repository sections.
- Update the existing section file if revised; never create a duplicate.
- Do not commit unchanged content.
