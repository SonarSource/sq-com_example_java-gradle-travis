# Java Gradle-based project analyzed on SonarCloud using Travis

[![Build status](https://travis-ci.org/SonarSource/sq-com_example_java-gradle-travis.svg?branch=master)](https://travis-ci.org/SonarSource/sq-com_example_java-gradle-travis) [![Quality Gate](https://sonarcloud.io/api/project_badges/measure?project=com.sonarqube.examples.java-gradle-travis-project&metric=alert_status)](https://sonarcloud.io/dashboard/index/com.sonarqube.examples.java-gradle-travis-project)

#### This project is analysed on [SonarCloud](https://sonarcloud.io)!

It is very easy to run an analysis on a Gradle-based project and push it to SonarCloud:

1. Declare the `org.sonarqube` plugin in your `build.gradle` file
2. In your `.travis.yml` file:
   1. Activate the [Travis Add-on](https://docs.travis-ci.com/user/sonarcloud/)
   2. Run `./gradlew sonarqube` at some point of time in the `script` section

You can take a look at the
[build.gradle](https://github.com/SonarSource/sq-com_example_java-gradle-travis/blob/master/build.gradle)
and
[.travis.yml](https://github.com/SonarSource/sq-com_example_java-gradle-travis/blob/master/.travis.yml)
files of this project to see it in practice.
