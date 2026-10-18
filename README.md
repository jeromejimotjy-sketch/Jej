# Vector Fabric Client — Minecraft 1.21.1

Client-side Fabric mod for Minecraft 1.21.1. Built for Fabric Loader and Fabric API.

## Build

Use Java 21 and Gradle 8.10.2, then run `gradle build`. The remapped mod JAR is in `build/libs/`.

GitHub Actions can build it automatically using the included workflow at `.github/workflows/build.yml`. Upload the project files (including `.github`) to your repository, then open Actions and run **Build Vector Fabric mod**. Download the `Vector-Minecraft-1.21.1` artifact and extract the JAR for your launcher's `mods` folder.

## Menu

Press Right Shift to open/close the Vector menu. The new interface uses a dark navy/purple module-list layout, sidebar categories, module toggles, search filtering, and a list/grid control. The menu deliberately does not request vanilla background blur.

This project is a lightweight client-side UI shell. Some listed modules are placeholders and do not implement gameplay functionality.
