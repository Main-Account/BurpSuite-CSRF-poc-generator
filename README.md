# BurpSuite-CSRF-poc-generator
A Burp Suite extension for CSRF proof of concepts


## Introduction
Many times we want to create a CSRF PoC and we don't have the Burp Pro version installed, so this plugin is helpful for you, no need for Burp Suite Pro.

## Setup
Download the jar file located in the releases section and import it in the extender option of burp suite. For more information about how to use extender option see the [official documentation](https://portswigger.net/burp/documentation/desktop/tools/extender#loading-and-managing-extensions)

## Local compilation
If you want to compile the code yourself, you need to have [maven](https://maven.apache.org/) installed and run the following command in the base directory of the project:

```console
$ mvn clean install
```
