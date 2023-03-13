## Introduction

This is a parent POM that is shared across my GitHub repositories.<br>
This is used to centralize versions, plugin setup and common properties to avoid redundancies or duplicate
configurations using inheritance between pom files. It helps in easy maintenance in long term.

## Dependent repositories

1. [test-automation-fwk](../../../test-automation-fwk)
2. [test-java2robot-adapter](../../../test-java2robot-adapter)
3. [test-webdriver-downloader](../../../test-webdriver-downloader)
4. [test-robot-framework](../../../test-robot-framework)
5. [test-testng-framework](../../../test-testng-framework)

## Usage

In the same directory, clone this repository first and after that clone other dependent repositories.

```shell
git clone git@github.com:ndviet/test-parent-pom.git
```
