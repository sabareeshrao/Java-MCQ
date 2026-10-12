# Chapter 1 — Java Installation and First Program

## Section 1.3 — Downloading and Installing the Java JDK

- **Section ID:** CH01-S03
- **Transcript:** 00:00:58–00:01:56
- **Audience:** Recent CSE graduate; no industry experience required
- **Questions and answers:** 5
- **Source:** Uploaded Java course transcript

### Context

The Java Development Kit (JDK) must be downloaded and installed as part of preparing a Java development environment.

The installation follows a straightforward process using the Oracle JDK distribution.

1. Search online for `jdk download` and navigate to the Oracle JDK download page. A direct link to the download page is another option.
2. Select the JDK version. **JDK 23** was identified as the latest version at the time of the demonstration, not necessarily the latest version today.
3. Select the installer corresponding to the operating system. For a Windows computer, the demonstrated choice is the **Windows 64-bit installer**.
4. Download the installer executable and wait until the download finishes.
5. Open the downloaded executable, proceed through the installation using **Next**, and finish once the JDK installation succeeds.
6. Close the installer after successful installation.

**Installation flow:** Find Oracle JDK download page → choose JDK version (JDK 23 in the demonstration) → choose appropriate operating system (Windows 64-bit shown) → download installer → open executable → Next → Next → successful installation → close installer.

### Sequenced Questions and Answers

**CH01-S03-Q01.** How can a Java developer locate the JDK installer, and which JDK provider is used in this installation workflow?

**Answer:** Search for `jdk download` using a search engine and navigate to the **Oracle JDK download page**. Alternatively, a direct link to that page can be used. Oracle is the JDK provider selected for this installation.

**CH01-S03-Q02.** JDK 23 is identified as the latest version in the installation example. Why should a developer not assume that JDK 23 will always be the latest available release?

**Answer:** JDK 23 was identified as the latest version **at the time of the demonstration**. That version reference is time-dependent, so it should not be interpreted as a permanent statement about the latest JDK release.

**CH01-S03-Q03.** What system-specific information must be considered when choosing a JDK installer, and what installer is selected for the Windows environment?

**Answer:** The installer must correspond to the computer's **operating system**. The demonstrated machine runs Windows, so the **Windows 64-bit installer** is selected. A computer running a different operating system should use an installer intended for that system.

**CH01-S03-Q04.** After selecting the appropriate JDK installer, describe the sequence required to complete the installation. How is successful completion identified?

**Answer:** The installation sequence is:

1. Download the selected installer.
2. Wait for the download to complete.
3. Open the downloaded executable.
4. Proceed through the installation screens by selecting **Next**, then **Next**.
5. Confirm that the JDK has been successfully installed.
6. Close the installer.

The successful-installation confirmation marks completion of the demonstrated process.

**CH01-S03-Q05.** A CSE graduate uses a computer running a different operating system but selects the Windows 64-bit installer because that is the option shown in the example. After downloading it, the graduate assumes Java has been installed. Identify the two mistakes and describe the correct approach.

**Answer:**

**Mistake 1 — Incorrect installer selection:** The installer was chosen based on another computer's operating system rather than the graduate's actual operating system. The correct download must match the system being used.

**Mistake 2 — Confusing downloading with installation:** Downloading an installer does not mean the JDK installation has been completed.

**Correct approach:** Select the operating-system-appropriate JDK installer, download it, run the installation procedure for that installer, and confirm successful installation before treating the setup as complete.

### Section boundary

This section covers obtaining and installing the JDK. It does not yet cover installing IntelliJ IDEA, configuring environment variables, executing Java programs, or checking installation with terminal commands.

Those subjects must not be used to expand the questions in this section.
