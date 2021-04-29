# UKGradle
##### Forked from [ForgeGradle](https://github.com/MinecraftForge/ForgeGradle)

This is a fork of ForgeGradle 2.1, meant to continue support for 
old versions of Minecraft such as 1.7.10.

*Compiled for Java 8/Gradle 3.5.*

Fixes applied include:
- Replaced old Forge Maven links with `https://maven.rainyville.org`, 
which is my own repository
- Fixed FernFlower task
- Minor code cleanup

Future goals:
- [ ] Migrate AWS links to the new API
- [ ] Fix support for 1.6.4
- [ ] Add support for newer versions of Gradle
- [ ] Add support for IntelliJ/Eclipse run tasks