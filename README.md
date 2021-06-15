# gradle-init
Generate new project for rapid development using Gradle

## getting help

```bash
gradle help --task :init
```

```
> Task :help
Detailed task information for :init

Path
     :init

Type
     InitBuild (org.gradle.buildinit.tasks.InitBuild)

Options
     --dsl     Set the build script DSL to be used in generated scripts.
               Available values are:
                    groovy
                    kotlin

     --package     Set the package for source files.

     --project-name     Set the project name.

     --split-project     Split functionality across multiple subprojects?

     --test-framework     Set the test framework to be used.
                          Available values are:
                               junit
                               junit-jupiter
                               kotlintest
                               scalatest
                               spock
                               testng

     --type     Set the type of project to generate.
                Available values are:
                     basic
                     cpp-application
                     cpp-library
                     groovy-application
                     groovy-gradle-plugin
                     groovy-library
                     java-application
                     java-gradle-plugin
                     java-library
                     kotlin-application
                     kotlin-gradle-plugin
                     kotlin-library
                     pom
                     scala-application
                     scala-library
                     swift-application
                     swift-library

Description
     Initializes a new Gradle build.

Group
     Build Setup

BUILD SUCCESSFUL in 631ms
1 actionable task: 1 executed
```
