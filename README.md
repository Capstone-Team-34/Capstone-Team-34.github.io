# Slicer4J IntelliJ Plugin Maven Repository

## Updating Repository

1. Download slicer4j-intellij-plugin repository (https://github.com/Capstone-Team-34/slicer4j-intellij-plugin) and open Gradle Tool Window

2. Make sure Project SDK and Gradle are set to JVM 11  

&emsp;Project SDK: <kbd>File</kbd> > <kbd>Project Structure</kbd>

&emsp;<img width="1021" alt="image" src="https://user-images.githubusercontent.com/42990646/165678336-05d412c4-dcf1-4d1e-aa94-de10250ab006.png">

&emsp;Gradle setting: <kbd>IntelliJ IDEA</kbd> > <kbd>Preferences</kbd> > <kbd>Build, Execution, Deployment </kbd> > <kbd>Build Tools</kbd> > <kbd>Gradle</kbd>

&emsp;<img width="1031" alt="image" src="https://user-images.githubusercontent.com/42990646/165678489-8b44b761-4f5f-48f6-95a5-18a37a88b408.png">

3. Run gradle task `buildPlugin` 
<img width="1440" alt="Screen Shot 2022-04-24 at 8 18 10 PM" src="https://user-images.githubusercontent.com/42990646/165015217-99d0bf17-9992-4f81-a374-c9dba9867e0b.png">


4. When the build is finished, copy `build/distributions/slicer4j-intellij-plugin-<VERSION>.zip` in slicer repo to `docs/plugins/` in this repo 
5. Update `docs/updatePlugins.xml` in this repo using `pluginVersion`, `pluginSinceBuild`, `pluginUntilBuild` from `build/patchedPluginXmlFiles/plugin.xml` in slicer repo 

