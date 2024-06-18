# MultiGitProjectManager

## Table of contents

0. [Introduction](#introduction)
1. [Before Installation](#before-installation)
2. [Installation](#installation)
3. [Use](#use)
4. [Aditional Info](#aditional-info)

## Introduction

MultiGitProjectManager (MGPM) helps you manage hundreds of projects to keep in sync with their remote repository.

-----------

## Before Installation

In order for this program to work as expected, you must have installed Gradle in your commputer. If you have not installed this build system yet, here is a link on the latest version and a youtube video on how to install it.


**Gradle download:** https://gradle.org/install/


**Youtube video:** https://www.youtube.com/watch?v=esygQzIRKBQ

-----------

## Installation

1. Download the github zip containing the code of the software and extract the files wherever you desire in your computer.
2. One of the files downloaded will be named "mgpm.yml". You have to change it with the information of the repositories you want this program to sync (the example "mgpm.yml" file only has two repositories, but you can include as many as you need).
There is additional information regarding this matter in the wiki (https://github.com/Sw-Evolution/mgpm/wiki/mgpm.yml).
3. Download the latest version of the build from the direct link (https://github.com/Sw-Evolution/mgpm/releases/download/1.3.0/mgpm-1.3.0.jar) or from the releases page (https://github.com/Sw-Evolution/mgpm/releases), and include the .jar file in the same folder as the "mgpm.yml" file.
4. To run the program, go to the folder where the "mgpm.yml" is located and open a terminal. Once you have done that, write one the commands that this software uses, for example `java -jar mgpm-1.3.0.jar -h` (there are some of this command in the [use](#use) section).

-----------

## Use
This section focuses on the commands you will be able to use in regard to MultiGitProjectManager. Some of them are:
1. `java -jar mgpm-1.3.0.jar -i` is used to initialize or clone missing repositories.
2. `java -jar mgpm-1.3.0.jar -u` is used to update all repositories.
3. `java -jar mgpm-1.3.0.jar -s` is used to show detailed status of branches.
4. `java -jar mgpm-1.3.0.jar -q` is used to suppress output.
All the other commands can be visualized accessing the help menu option: `java -jar mgpm-1.3.0.jar -h`.

-----------

## Aditional Info

This software was originally made by Tristan Lins, and has been modified (especially to update some obsolete code that interfered with its proper functioning) by Sergio Rodríguez Gil, Javier Cai Lin y Carlos García Pérez.