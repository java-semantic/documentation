# Setting up environment.

If you do not have JDK installed.

You can find the files in the links below.
Java version: JDK 11

Preferred JDK: [Redhat](https://developers.redhat.com/products/openjdk/download).


[Open JDK](https://jdk.java.net/java-se-ri/11) | [Oracle](https://www.oracle.com/za/java/technologies/javase-jdk11-downloads.html) |

For your information:
https://www.baeldung.com/oracle-jdk-vs-openjdk

## IDE

- Install IntellJ IDE.
[Download](https://www.jetbrains.com/idea/download/)

- Choose your platform.
- Download and follow the instructions described in the above link 😊.
- Using the community version should be fine, as the required plugins will be available.

#### Plugin	Home page
* [Lombok](https://plugins.jetbrains.com/plugin/6317-lombok)
* [MapStruct Support](https://plugins.jetbrains.com/plugin/10036-mapstruct-support)
* [Maven Wrapper Support](https://plugins.jetbrains.com/plugin/10633-maven-wrapper-support)

Plugins can be download and installed via the Intellj IDE.
File -> Settings -> Plugins -> Type your desired plugin in search bar, install and apply.

Restart IntelliJ to apply the plugins.

## Styles
The code style should be handled by the git formatter (maven dependency) to apply the correct styles. The styles will be applied once maven is run install or when a
 git commit is initiated.
[Cosium Github repo](https://github.com/Cosium/git-code-format-maven-plugin)

Why the git code formatter? We work with people, who will forget at times to format their code.

### Do we need maven?
Ideally no, as the project will have a maven wrapper. The idea is to prevent dependencies in your environment, and the project should be dependent on the maven
 wrapper. Just pull and play.

