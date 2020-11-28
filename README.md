# checkstyle

Inspired by the [checkstyle](https://github.com/checkstyle/checkstyle) project.

This repository aims to format personal code in a consistent way with:

- style configuration file
  - Java: [google_checks.xml](./java/google_checks.xml)
- auto code formatting mechanism in text editors

Currently, we are using Visual Studio Code.

Most features we use are offerd by:

- Language Support for Java(TM) by Red Hat

Java code style configuration file can by applied via:

- ctrl + shift + p
- Enter commands: Java:Open Java formatter settings
- Replaced with: /your/local/path/checkstyle/java/google_checks.xml

Auto format can be configured via:

- Open: Settings - Text Editor - Formatting
- Tick the Editor: Format on save box

Auto organize imports can be configured via:

- Open: Settings - Extensions - Java 
- Tick the Java> Save Actions: organize imports box