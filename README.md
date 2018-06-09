# pwned-java

Example of how to use the [PwnedPasswords4j](https://github.com/nbaars/pwnedpasswords4j) library. Based on the haveibeenpwned API - [https://haveibeenpwned.com/](https://haveibeenpwned.com/)

## Running the project

Make sure you have Maven installed. You can download it here: https://maven.apache.org/download.cgi
```
mvn --version
```

Clone this repo.

Package the project:
```
mvn package
```

Run the program:
```
java -cp target/pwned-1.0-SNAPSHOT-jar-with-dependencies.jar me.krobinson.App
```
