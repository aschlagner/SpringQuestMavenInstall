# SEA8 - SpringQuest - Maven install

Challenge: Create a pom.xml file for a new Java project and build your program

### Create a runnable Java program

Your pom.xml should work and create a .jar file with an executable Java program. You will have to specify the **main class** in the manifest of the jar file and you need to add the **maven-jar-plugin** to modify and extend the default manifest file.

The Java program can simply print a "Hello World" message to the screen - it just has to be a runnable Java program.

### Implementation

Add information about the **implementation** (title, version and vendor) to the manifest file of the .jar file.

### Author and Timestamp

Add information about the author and date of creation to the manifest file of the .jar file

## Acceptance criteria

- You created a Java project that uses the maven build tool
- The Java project produces a runnable Java program with _mvn clean package_
- You added a dependency to your project and check your local repository cache for the downloaded binaries - run _ls -l ..._ to list the downloaded files.
- You added a plugin to the pom.xml to enhance the content of the MANIFEST.MF file
- Everything is in a git repository and available on GitHub
