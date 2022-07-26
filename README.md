# Remote lint config demo

Demonstrates how to use SwiftLint from remote config repository and override some rules with local config. This can allow teams to have one hosted configuration used as a base and use the local config to add new or re-adjust some existing rules.

## Basic info

Main config is specified inside [.swiftlint.yml](https://github.com/hhrvoic/remote_lint_demo/blob/main/.swiftlint.yml) file. This config specifies links to the parent (base) and the child (specialized/override) config. Remote config file (Infinum's specification) is hosted at this [link](https://infinum.com/handbook/resources/ios/swiftlint.yml). Local config that overrides remote one is defined inside [.swiftlint_overrides.yml](https://github.com/hhrvoic/remote_lint_demo/blob/main/.swiftlint_overrides.yml) file.