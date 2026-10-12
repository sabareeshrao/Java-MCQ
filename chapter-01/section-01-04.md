# Chapter 1 — Java Installation and First Program

## Section 1.4 — Downloading and Installing IntelliJ IDEA

- **Section ID:** CH01-S04
- **Transcript:** 00:01:56–00:03:34
- **Audience:** Recent CSE graduate; no industry experience required
- **Questions and answers:** 10 (progressively sequenced; no difficulty categories)
- **Source:** Uploaded Java course transcript

### Context

After the JDK installation, the next part of a Java coding setup is the **integrated development environment (IDE)**. **IntelliJ IDEA** is selected for the coding workspace. The walkthrough starts by searching for `IntelliJ download` and opening a download result. If the opened page is not the download page, the **Get IntelliJ** link at the top right is used to reach it.

The download page shown at the time offers a **30-day trial** and a **free Community Edition** farther down the page. The free edition is selected, and the installer appropriate for the operating system is downloaded. In the Windows example, this is an **executable installer**.

After the download completes, the executable is opened. The installation wizard allows the installation **destination folder** to be chosen or left unchanged, offers an optional **desktop shortcut**, and presents a **PATH variable** option. PATH is described as telling the operating system where to find executable files. This can be useful when running Java code from the **Command Prompt or terminal**, but that workflow is not used in the presented course, so the option can be deferred and updated later.

Installation continues with **Next** and **Install**. At the end, an option is selected to **run IntelliJ** immediately, followed by **Finish**.

**Workflow:** Search for IntelliJ download → navigate to download page → locate free Community Edition rather than the trial → select an OS-appropriate installer → download and open executable → choose destination → optionally create desktop shortcut / update PATH → Next → Install → choose to run IntelliJ → Finish.

**Historical interface note:** The trial and Community Edition choices describe the download page shown in this source, not a guarantee about the current JetBrains website.

### Sequenced Questions and Answers

**CH01-S04-Q01.** Once the JDK setup is complete, which IDE is selected for Java development, and how is its download page initially located?

**Answer:** **IntelliJ IDEA** is selected. Search online for `IntelliJ download` and open the relevant download result.

**CH01-S04-Q02.** A search result opens an IntelliJ website page but not the download page. What navigation option is provided to reach the correct page?

**Answer:** Use **Get IntelliJ** at the top right of the site to reach the download page.

**CH01-S04-Q03.** A recent graduate wants the no-cost IntelliJ option shown in the download walkthrough rather than the time-limited offer. Which edition should be selected, and how is it located?

**Answer:** Scroll below the displayed **30-day trial** to find the **free Community Edition**, then choose that edition. These are the options shown in the source's download-page interface.

**CH01-S04-Q04.** What must be checked when choosing an IntelliJ download, and what download format is used in the Windows installation example?

**Answer:** Choose the download appropriate for the computer's **operating system**. The Windows example uses an **executable installer**.

**CH01-S04-Q05.** After the IntelliJ executable finishes downloading, what are the next steps through the installation-destination screen? Is changing the destination mandatory in this workflow?

**Answer:** Open the downloaded executable, select **Next**, and review or choose the **destination folder**. Changing it is not mandatory in this walkthrough: the existing/default folder is kept, and **Next** is selected.

**CH01-S04-Q06.** What optional convenience feature can be selected in the installer before proceeding, and what is its stated purpose?

**Answer:** A **desktop shortcut** can be created for convenience. It is an optional installation choice, not a required Java programming concept.

**CH01-S04-Q07.** An IntelliJ installation screen offers to update the PATH variable. What is PATH described as doing, and in what type of workflow would the option be useful?

**Answer:** **PATH** tells the operating system where to find **executable files**. The option is described as useful when working from the **Command Prompt or terminal** to run Java code. The section does not specify exactly which executable path the installer would add.

**CH01-S04-Q08.** A graduate plans to follow the IntelliJ-based exercises without running Java code from the terminal. Must the PATH update be selected immediately, and can that choice be revisited?

**Answer:** **No immediate update is required in the presented workflow.** Because terminal-based execution is not planned for these exercises, the option is skipped for now. PATH can be updated later if needed.

**CH01-S04-Q09.** After reviewing the installer options, which actions complete the installation and start IntelliJ immediately?

**Answer:** Continue with **Next**, choose **Install**, and let the installation finish. Then select the checkbox to **run IntelliJ**, followed by **Finish**. This launches the IDE as part of completing the setup.

**CH01-S04-Q10.** A Windows-based CSE graduate wants the free IntelliJ edition, is happy with the default installation folder, wants quick desktop access, will not use terminal commands, and wants IntelliJ to open when installation ends. Describe the installation choices in the correct order.

**Answer:** Search for `IntelliJ download` and reach the download page (using **Get IntelliJ** if the search result opens another site page). Scroll to the **free Community Edition** beneath the trial offer and select the **Windows executable**. After downloading, open the executable and select **Next**. Keep the existing **destination folder**; enable the **desktop shortcut** for convenience. The **PATH update** can be deferred because terminal execution is not part of the planned workflow. Select **Next**, then **Install**; enable **Run IntelliJ** at completion and select **Finish**.

### Coverage rationale — Why 10 questions are sufficient

The complete 98-second transcript interval contains one practical workflow with a limited number of distinct choices. Ten progressively linked questions cover its **download discovery** (Q01–Q02), **trial versus free edition** (Q03), **operating-system-specific executable** (Q04), **installer launch and destination** (Q05), **desktop shortcut** (Q06), **PATH meaning and its relevance** (Q07–Q08), **finish and immediate launch** (Q09), and an **end-to-end decisions scenario** (Q10). Additional questions would mainly restate these same decisions rather than assess a new concept.

### Section boundary

The **IntelliJ welcome screen and creating a Java project** begin in the following section at 00:03:34. Java source files, code execution, and JVM details are not covered here. The answer set does not depend on modern website changes or unstated installer behavior.
