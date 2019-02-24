# Spring Clinet

A spring boot based project started with an empty folder.

## Initialize the directory structure of the project

Step 1: Created the below directories.

    src/main/java
    src/test/java
    src/main/resources/META-INF
    target/class

Step 2: Mark the source (`src/main/java`) and test (`src/test/java`) folders in your editor.

Step 3: Create a package `hello` in `src/main/java`.

Step 4: Creata the first Java class, `Application` within the `hello` package.

Step 5: Created `src/main/resources/META-INF/MANIFEST.MF`.

Step 6: Compile code using `javac -cp ./src/main/java src/main/java/**/*.java -d ./target/classes`.

Step 7: Build a jar using `jar cfm ./target/SpringClient-0.9.0.jar ./src/main/resources/META-INF/MANIFEST.MF -C ./target/classes .`.

Step 8: Execute the jar, `java -jar ./target/SpringClient-0.9.0.jar`. It would print `Hello Spring` on the command line.

## Add Maven

Step 9: Add `pom.xml` and fill it.

Step 10: Clean and build target and then package, run the application.

    $ mvn clean
    $ mvn package
    $ java -jar ./target/SpringClient-0.9.0.jar

Note: The Maven Shade Plugin is bound to the `package` phase and is used to package the artifact in an uber-jar,
      including its dependencies, and creates a shaded or renamed jar in the `target` directory.

## Add Spring Boot

Step 11: Add SpringBoot to the Application Class.