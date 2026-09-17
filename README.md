# Controller

A native macOS app for working with coding agents in project threads, with a file inspector and integrated terminal.

[Download the latest release](https://github.com/mweinbach/Controller/releases/latest)

## Requirements

- macOS 27 or later
- Apple silicon
- The coding tools you want to use installed on your system

Controller connects directly to installed Codex, Claude Code, Cursor, Grok, Factory Droid and OpenCode tools. Its agent clients and MCP tools run natively, with no Node runtime, npm packages, JavaScript workers or separate MCP helper required by Controller. Installed coding tools retain their own requirements. OpenCode uses its installed v2 background service without requiring a specific patch release.

## Install

1. Download `Controller-<version>-arm64.zip` from a release.
2. Unzip it and move `Controller.app` into Applications.
3. Install and sign in to your desired coding tool using its own setup instructions.
4. Open Controller, connect a provider in Settings, and add a project folder.

Controller is signed with Developer ID and notarized by Apple. Subsequent app updates use Sparkle. Choose **Controller → Check for Updates…** to check manually; Sparkle asks whether to check automatically.

## Support

[Report an issue](https://github.com/mweinbach/Controller/issues/new). Include the version, macOS version and steps to reproduce. Review any diagnostic report before posting it.

This repository contains release downloads, release notes and the signed update feed. Application source is maintained privately.
