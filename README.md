# JShell Standalone
JShell Standalone: Anything needed to run JShell independently is contained. The Java 9 runtime is included and compressed using the jlink tool.

Caveat: The default JShell editor is not available. An editor can be set in JShell e.g. with `/set editor C:/Program Files (x86)/Notepad++/notepad++.exe`

## Download
* Windows: [JShell jdk-9+180_windows](https://github.com/sgwerder/JShellStandalone/raw/master/release/JShell_jdk9%2B180_windows.zip)
* Linux: [JShell jdk-9+180_windows](https://github.com/sgwerder/JShellStandalone/raw/master/release/JShell_jdk9%2B180_linux.zip)

## Build

### Windows

* Checkout this repository. That directory will be referenced as \<repository-path>
* Install [Java JDK 9](http://jdk.java.net/9/)
* Set environment variable %JAVA_HOME% to the Java 9 installation directory:

  `set JAVA_HOME = C:\PROGRA~1\java\jdk-9`
* Open the command line
* Change directory to \<repository-path>
* Compile the project to \<repository-path>/mods/com.standalone.jshell:

  `javac -d ./mods/com.standalone.jshell ./src/com.standalone.jshell/module-info.java ./src/com.standalone.jshell/com/standalone/jshell/JShellStandalone.java`
  
  If successful, the compiled files can be found in \<repository-path>/mods.
  JShellStandalone.java is only used to have something to compile.
  More importantly the module-info.java contains dependencies on "jdk.zipfs" and jdk.jshell".
* Bundle the Java 9 runtime (**semicolon** as path separator):

  `jlink --module-path %JAVA_HOME%/jmods;./mods --add-modules com.standalone.jshell --output ./target --compress 2 --strip-debug --exclude-files *.diz --no-header-files --no-man-pages`
  
  If successful, the binaries can be found in \<repository-path>/target/bin.
  
* Run \<repository-path>/target/bin/jshell.exe

### Linux

* Checkout this repository. That directory will be referenced as \<repository-path>
* Install [Java JDK 9](http://jdk.java.net/9/), for apt-get early access see this [link](https://helpfromviraj.wordpress.com/2015/08/04/install-oracle-java-9-in-ubuntu-or-linux-jdk-9/)
* Set Java 9 to default, check with `java -version`
* In the terminal, change directory to \<repository-path>
* Compile the project to \<repository-path>\mods\com.standalone.jshell:

  `javac -d ./mods/com.standalone.jshell ./src/com.standalone.jshell/module-info.java ./src/com.standalone.jshell/com/standalone/jshell/JShellStandalone.java`
  
  If successful, the compiled files can be found in \<repository-path>/mods.
  JShellStandalone.java is only used to have something to compile.
  More importantly the module-info.java contains dependencies on "jdk.zipfs" and jdk.jshell".
* Bundle the Java 9 runtime (**colon** as path separator):

  `jlink --module-path /usr/lib/jvm/java-9-oracle/jmods:./mods --add-modules com.standalone.jshell --output ./target --compress 2 --strip-debug --exclude-files *.diz --no-header-files --no-man-pages`
  
  If successful, the binaries can be found in \<repository-path>/target/bin.
  
* Run jshell in \<repository-path>/target/bin/
  
  
  



