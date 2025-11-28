# Setting Up Java Development Environment (4/500)

## Editors vs IDEs
- Need a place to write Java code: editor or IDE.
- Editors: Notepad, WordPad, Notepad++, Edit+.
- IDE (Integrated Development Environment) includes code writing, running, compiling, debugging.
- Beginners may start with editors; for real projects, an IDE is better.
- Popular Java IDEs: VS Code (used in course), Eclipse, IntelliJ IDEA, NetBeans.
- Personal favorite: IntelliJ IDEA Ultimate (paid), Community version has limited features.
- VS Code chosen for being lightweight yet powerful.

## Java Compiler & JDK
- Need to compile Java code using JDK (Java Development Kit).
- Two JDK versions: Oracle’s proprietary and open-source variants (Corretto, others).
- Oracle JDK is free again and used in course.
- Java versions update every 6 months; basic language stays backward compatible.
- Choose Long-Term Support (LTS) version Java 17 over Java 19 for stability.

## Downloading & Installing
- Download JDK and VS Code via browser.
- Select OS-specific version: Windows, Mac (Intel or Apple chip), Linux.
- Installation is straightforward: mostly "Next" clicks.
- Windows users must set PATH environment variable pointing to JDK's bin folder.
- Verify installation by running `java --version` and `javac --version` in Command Prompt.

## VS Code Setup
- Popular IDE, familiar to many programmers.
- After install, launch VS Code.
- Install extensions as needed (first 4 default for beginners).
- Open terminal in VS Code and verify JDK by running `javac`.


-------


# First Java Code (7/500)

<img width="562" height="283" alt="image" src="https://github.com/user-attachments/assets/57d1cbf1-8509-496a-b49a-d5ebff214995" />

    jshell> /exit
    |  Goodbye

## VS Code Setup
- Open VS Code, select dark theme (eye-friendly).
- Explorer (left): project files/folders.
- Terminal (built-in): check Java setup (`java --version`, `javac --version`).
- Java 17 LTS confirmed working.

## Creating First Project
- Open folder → Desktop → Create "Course" folder.
- Create `hello.java` file (must use `.java` extension).
- VS Code suggests Java Extension Pack (optional, provides suggestions).

## JShell (Java 9+ Experimentation)
- Interactive tool for quick testing: `jshell`
- Basic operations: `2 + 3` → `5`, `9 - 6` → `3`
- Printing:
  - Numbers: `System.out.print(6);`
  - Text: `System.out.print("hello world");`
- **Key Rules:**
  - Text in double quotes `""`
  - End statements with semicolon `;`
  - `System.out.print()` for output

## Hello.java File (Project Building)
- `.java` files for real projects (not JShell).
- **Two-step process:** Compile → Run
- Compile: `javac hello.java` → **Error** (missing class declaration).

## Next Steps
- JShell good for experiments/learning.
- `.java` files need proper structure (class declaration) for compilation.
- Proper Hello World structure covered in next video.



-------





-------





-------





-------





-------





-------




