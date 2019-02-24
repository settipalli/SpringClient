# Spring Clinet

A spring boot based project started with an empty folder.

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
