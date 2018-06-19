# de.acetous.dependency-compliance

## Repository structure

This repository contains the plugin and a sanbox project for manual tests when editing the plugin.

### ./gradle-enforce-dependency-compliance-plugin

This is the actual plugin. Run some integration tests via:
```
> cd gradle-enforce-dependency-compliance-plugin
> gradlew check
```

### ./plugin-sandbox

This is a demo project which uses the plugin. The plugin is included in this build in order to test changes without the need to deploy the plugin first.
Run your manual tests here. You can change the sandbox project to demonstrate new features.

```
> cd plugin-sandbox
> gradlew dependencyComplicanceList
```