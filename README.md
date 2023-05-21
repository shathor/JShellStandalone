# JShell Standalone
Provides a standalone version of the JShell REPL. Anything needed to run JShell independently is contained, so there is no need to install the full JDK. A minimal Java runtime is embedded and compressed using the jlink tool.

This minimal version consists only of the modules necessary to run JShell: "java.base", "jdk.zipfs" and "jdk.jshell".
However the user can manually provide any JDK or custom module on startup with `--add-module`.

Note that the startup time of JShell 10 was significantly improved.

Caveat: The default JShell editor is not available. An editor can be set in JShell e.g. with `/set editor C:/Program Files (x86)/Notepad++/notepad++.exe`

## Download

Note that the mostly "General Availability" JDK (x64) releases are used and not always the newest patch releases.

### JDK 20+36

| OS | Size | JDK | Download |
| - | - | - | - |
| Windows | 29.3 MB | OpenJDK | [JShell_jdk20.36_windows.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-20%2B36/JShell_jdk20.36_windows.zip) |
| Linux | 30.9 MB | OpenJDK | [JShell_jdk20.36_linux.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-20%2B36/JShell_jdk20.36_linux.zip) |
### JDK 19.0.1+10

| OS | Size | JDK | Download |
| - | - | - | - |
| Windows | 29.0 MB | OpenJDK | [JShell_jdk19.0.1.10_windows.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-19.0.1%2B10/JShell_jdk19.0.1.10_windows.zip) |
| Linux | 30.6 MB | OpenJDK | [JShell_jdk19.0.1.10_linux.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-19.0.1%2B10/JShell_jdk19.0.1.10_linux.zip) |
### JDK 18.0.2+9

| OS | Size | JDK | Download |
| - | - | - | - |
| Windows | 27.8 MB | OpenJDK | [JShell_jdk18.0.2.9_windows.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-18.0.2%2B9/JShell_jdk18.0.2.9_windows.zip) |
| Linux | 29.3 MB | OpenJDK | [JShell_jdk18.0.2.9_linux.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-18.0.2%2B9/JShell_jdk18.0.2.9_linux.zip) |
### JDK 17.0.1+12

| OS | Size | JDK | Download |
| - | - | - | - |
| Windows | 27.2 MB | OpenJDK | [JShell_jdk17.0.1.12_windows.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-17.0.1%2B12/JShell_jdk17.0.1.12_windows.zip) |
| Linux | 28.7 MB | OpenJDK | [JShell_jdk17.0.1.12_linux.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-17.0.1%2B12/JShell_jdk17.0.1.12_linux.zip) |
### JDK 16.0.1+9

| OS | Size | JDK | Download |
| - | - | - | - |
| Windows | 26.5 MB | OpenJDK | [JShell_jdk16.0.1.9_windows.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-16.0.1%2B9/JShell_jdk16.0.1.9_windows.zip) |
| Linux | 28.1 MB | OpenJDK | [JShell_jdk16.0.1.9_linux.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-16.0.1%2B9/JShell_jdk16.0.1.9_linux.zip) |
### JDK 15+36

| OS | Size | JDK | Download |
| - | - | - | - |
| Windows | 26.1 MB | OpenJDK | [JShell_jdk15.36_windows.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-15%2B36/JShell_jdk15.36_windows.zip) |
| Linux | 28.0 MB | OpenJDK | [JShell_jdk15.36_linux.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-15%2B36/JShell_jdk15.36_linux.zip) |
### JDK 14.0.1+7

| OS | Size | JDK | Download |
| - | - | - | - |
| Windows | 29.5 MB | AdoptOpenJDK | [JShell_jdk14.0.1.7_windows.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-14.0.1%2B7/JShell_jdk14.0.1.7_windows.zip) |
| Linux | 27.6 MB | AdoptOpenJDK | [JShell_jdk14.0.1.7_linux.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-14.0.1%2B7/JShell_jdk14.0.1.7_linux.zip) |
### JDK 13.0.1+9

| OS | Size | JDK | Download |
| - | - | - | - |
| Windows | 25.7 MB | AdoptOpenJDK | [JShell_jdk13.0.1.9_windows.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-13.0.1%2B9/JShell_jdk13.0.1.9_windows.zip) |
| Linux | 27.5 MB | AdoptOpenJDK | [JShell_jdk13.0.1.9_linux.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-13.0.1%2B9/JShell_jdk13.0.1.9_linux.zip) |
### JDK 12+33

| OS | Size | JDK | Download |
| - | - | - | - |
| Windows | 25.6 MB | OpenJDK | [JShell_jdk12.33_windows.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-12%2B33/JShell_jdk12.33_windows.zip) |
| Linux | 28.0 MB | OpenJDK | [JShell_jdk12.33_linux.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-12%2B33/JShell_jdk12.33_linux.zip) |
### JDK 11+28

| OS | Size | JDK | Download |
| - | - | - | - |
| Windows | 24.3 MB | OpenJDK | [JShell_jdk11.28_windows.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-11%2B28/JShell_jdk11.28_windows.zip) |
| Linux | 26.4 MB | OpenJDK | [JShell_jdk11.28_linux.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-11%2B28/JShell_jdk11.28_linux.zip) |
### JDK 10+46

| OS | Size | JDK | Download |
| - | - | - | - |
| Windows | 23.6 MB | OracleJDK | [JShell_jdk10.46_windows.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-10%2B46/JShell_jdk10.46_windows.zip) |
| Linux | 26.2 MB | OpenJDK | [JShell_jdk10.46_linux.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-10%2B46/JShell_jdk10.46_linux.zip) |
### JDK 9+180

| OS | Size | JDK | Download |
| - | - | - | - |
| Windows | 23.0 MB | OracleJDK | [JShell_jdk9.180_windows.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-9%2B180/JShell_jdk9.180_windows.zip) |
| Linux | 25.4 MB | OpenJDK | [JShell_jdk9.180_linux.zip](https://github.com/shathor/JShellStandalone/releases/download/jdk-9%2B180/JShell_jdk9.180_linux.zip) |

## Build

### Windows

* Checkout this repository. That directory will be referenced as \<repository-path>
* Install [Java JDK 9 or higher](http://jdk.java.net/)
* Set environment variable %JAVA_HOME% to the Java installation directory. Replace <version> with the installed version:

  `set JAVA_HOME = C:\PROGRA~1\java\jdk-<version>`
  
* Add %JAVA_HOME% to the %PATH%, if it is not already:

  `set PATH = "%PATH%;%JAVA_HOME%\bin"`
* Open the command line
* Check if Java is accessible with `java -version`
* Change directory to \<repository-path>
* Compile the project to \<repository-path>/mods/com.standalone.jshell:

  `javac -d ./mods/com.standalone.jshell ./src/com.standalone.jshell/module-info.java ./src/com.standalone.jshell/com/standalone/jshell/JShellStandalone.java`
  
  If successful, the compiled files can be found in \<repository-path>/mods.
  JShellStandalone.java is only used to have something to compile.
  More importantly the module-info.java contains dependencies on "jdk.zipfs" and jdk.jshell".
* Bundle the Java runtime (**semicolon** as path separator):

  `jlink --module-path "%JAVA_HOME%/jmods;./mods" --add-modules com.standalone.jshell --output ./target --compress 2 --strip-debug --no-header-files --no-man-pages`
  
  If successful, the binaries can be found in \<repository-path>/target/bin.
  
* Run \<repository-path>/target/bin/jshell.exe

### Linux

* Checkout this repository. That directory will be referenced as \<repository-path>
* binutils need to be installed for objcopy
* Install [Java 9 or higher](http://jdk.java.net/). E.g. [How to manually install Java on Ubuntu](https://thishosting.rocks/install-java-ubuntu/#manually).
* Set the installed Java to default, check with `java -version`
* In the terminal, change directory to \<repository-path>
* Compile the project to \<repository-path>/mods/com.standalone.jshell:

  `javac -d ./mods/com.standalone.jshell ./src/com.standalone.jshell/module-info.java ./src/com.standalone.jshell/com/standalone/jshell/JShellStandalone.java`
  
  If successful, the compiled files can be found in \<repository-path>/mods.
  JShellStandalone.java is only used to have something to compile.
  More importantly the module-info.java contains dependencies on "jdk.zipfs" and jdk.jshell".
* Bundle the Java runtime (**colon** as path separator):

  `jlink --module-path $JAVA_HOME/jmods:./mods --add-modules com.standalone.jshell --output ./target --compress 2 --strip-java-debug-attributes --no-header-files --no-man-pages`
  
  If successful, the binaries can be found in \<repository-path>/target/bin.
  
* Run jshell in \<repository-path>/target/bin/
  
  
  



