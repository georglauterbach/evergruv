# Evergruv - Agent Guide

This project defines a color scheme based on Everforest Light & Gruvbox Material Dark. The color palette and its application has been altered.

This repository defines the colors and provides a VS Code extension. Other projects, like hermes (see below), implement the color scheme for other tools.

The VS Code themes are templated; the templates can be found in [`templates/`](./templates). The theme files are generated with [`generate.sh`](./generate.sh). When you make changes, update the templates and generate the new theme.

## Repository Layout

|Path|Purpose|
|:-|:-|
|`.github/`|GitHub-related content like CI/CD, issues, etc.|
|`CHANGELOG.md`|Keep a Changelog history|
|`cspell.config.yaml`|Spell-check configuration|
|`README.md`|Project description|
|`assets/`|contains "advertisement" material|
|`templates/`|contains file that are updated by `generate.sh`|
|`themes/`|contains an actual theme definition for VS Code|
