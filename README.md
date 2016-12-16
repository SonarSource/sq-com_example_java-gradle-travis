# Java Gradle-based project analyzed on SonarQube.com using Travis

[![Build status](https://travis-ci.org/SonarSource/sq-com_example_java-gradle-travis.svg?branch=master)](https://travis-ci.org/SonarSource/sq-com_example_java-gradle-travis) [![Quality Gate](https://sonarqube.com/api/badges/gate?key=com.sonarqube.examples.java-gradle-travis-project)](https://sonarqube.com/dashboard/index/com.sonarqube.examples.java-gradle-travis-project)

#### This project is analysed on [SonarQube.com](https://sonarqube.com)!

It is very easy to run an analysis on a Gradle-based project and push it to SonarQube.com:

1. Declare the `org.sonarqube` plugin in your `build.gradle` file
2. In your `.travis.yml` file:
  1. Activate the [SonarQube.com Travis Add-on](https://docs.travis-ci.com/user/sonarqube/)
  2. Run `./gradlew sonarqube` at some point of time in the `script` section

You can take a look at the
[build.gradle](https://github.com/SonarSource/sq-com_example_java-gradle-travis/blob/master/build.gradle)
and 
[.travis.yml](https://github.com/SonarSource/sq-com_example_java-gradle-travis/blob/master/.travis.yml)
files of this project to see it in practice.

### License

Copyright 2008-2016 SonarSource.

Licensed under the [GNU Lesser General Public License, Version 3.0](http://www.gnu.org/licenses/lgpl.txt)