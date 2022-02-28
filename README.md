# Slicer4J IntelliJ Plugin Maven Repository

The maven repo should be set in intellij to <https://capstone-team-34.github.io/updatePlugins.xml>

## Updating Repository

1. Run gradle task `buildPlugin`
2. copy `build/distributions/slicer4j-intellij-plugin-<VERSION>.zip` to `docs/plugins/`
3. Update `docs/updatePlugins.xml` from `build/patchedPluginXmlFiles/plugin.xml`


