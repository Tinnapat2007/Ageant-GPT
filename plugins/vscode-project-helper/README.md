# VS Code Project Helper

A lightweight Codex plugin that helps you understand, debug, and improve projects available in your local workspace. It works with a project open in VS Code when the same project files are accessible to Codex.

## What it does

- Inspects relevant project files and follows repository instructions such as `AGENTS.md`.
- Explains structure and behavior, and helps diagnose bugs.
- Makes focused, maintainable code changes while preserving unrelated work.
- Considers performance when a concrete bottleneck is identified.
- Avoids reading secrets and does not publish, deploy, or commit your project for you.

This plugin provides workflow guidance; it does not create a direct connection to the VS Code editor. Codex must have access to the project files in its active workspace.

## Install

Clone this repository and load `plugins/vscode-project-helper` as a local plugin in a plugin host that supports Codex plugins. The folder contains `plugin.json` and the `skills/` directory. Exact installation steps depend on the host and its current plugin catalog.

To use it with a project, open or attach that project's folder as the active Codex workspace. Then ask Codex to explain, debug, or improve the project.

## Use with any repository

The helper is repository-agnostic. Anyone can clone or fork this repository, install the plugin, and open their own project workspace. It does not bundle or upload the user's source code.

## Development

Manifest: `plugin.json`  
Workflow instructions: `skills/vscode-project-workflow/SKILL.md`

To contribute, fork the repository, make a focused change, and open a pull request. Keep the plugin usable without project-specific assumptions or additional dependencies.

## License

Released under the MIT License. See [LICENSE](LICENSE).
