# BDD in Action Second Edition - Chapter 1

![](https://github.com/bdd-in-action-second-edition/chapter-1/workflows/Maven%20Build/badge.svg)

## Code samples

This repository contains the sample code used in chapter 1 of [BDD in Action 2nd Edition](https://www.manning.com/books/bdd-in-action-second-edition).

### Required software
To run the sample code, you will need to install [Java 8 or higher](https://www.oracle.com/technetwork/java/javase/downloads/index.html), and [Maven](https://maven.apache.org). You can find [instructions for installing Maven here](https://maven.apache.org/install.html).

### Running the sample code

To run the sample project from the command line, open a command line window in the [online-banking](online-banking) directory and run the following command:
```
mvn clean verify
```

You should see some console output listing the executed tests. To view the full Serenity BDD report, open `target/site/serenity/index.html`.
