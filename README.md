# Slicer4J IntelliJ Plugin Maven Repository

## Updating Repository

1. Download slicer4j-intellij-plugin repository (https://github.com/Capstone-Team-34/slicer4j-intellij-plugin) and open Gradle Tool Window
2. Run gradle task `buildPlugin` 
<img width="1440" alt="Screen Shot 2022-04-24 at 8 18 10 PM" src="https://user-images.githubusercontent.com/42990646/165015217-99d0bf17-9992-4f81-a374-c9dba9867e0b.png">


3. When the build is finished, copy `build/distributions/slicer4j-intellij-plugin-<VERSION>.zip` in slicer repo to `docs/plugins/` in this repo 
4. Update `docs/updatePlugins.xml` in this repo using `pluginVersion`, `pluginSinceBuild`, `pluginUntilBuild` from `build/patchedPluginXmlFiles/plugin.xml` in slicer repo 
