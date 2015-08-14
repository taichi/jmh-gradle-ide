# JMH & Gradle & IDE(Eclipse or IDEA) project template

this project is sample of [JMH](http://openjdk.java.net/projects/code-tools/jmh/) gradle plugin & IDEs.

this sample contains undocumented tricks.

## Setup IDE files

    gradlew eclipse
    gradlew idea

## Run Benchmark

### with Gradle

    gradlew jmh

### without Gradle

    gradlew jmhjar
    java -jar build/libs/jmh-gradle-ide-jmh.jar

### on Eclipse

select `HelloBenchmark` and `Run As` > `Java Application`

# Depends on

* [melix/jmh-gradle-plugin](https://github.com/melix/jmh-gradle-plugin)
* [johnrengelman/shadow](https://github.com/johnrengelman/shadow)
* [tbroyer/gradle-apt-plugin](https://github.com/tbroyer/gradle-apt-plugin)

# License

Apache License, Version 2.0
