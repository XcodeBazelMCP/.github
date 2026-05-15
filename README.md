<p align="center">
  <img src="assets/LOGO.png" alt="XcodeBazelMCP" width="200">
</p>

# XcodeBazelMCP

A Model Context Protocol (MCP) server and CLI for Bazel-based Apple platform development. Ships 112 tools across 19 workflow categories covering iOS, macOS, tvOS, watchOS, visionOS, and Swift Package Manager.

## What It Provides

- **Build & Run** — Build, install, launch, and stop iOS/macOS apps on simulators and physical devices.
- **Test & Coverage** — Run unit/UI/build tests with filtering, streaming output, and code coverage.
- **Simulator Management** — Boot, shutdown, erase, configure location/appearance/status bar.
- **Physical Device** — Full device lifecycle via `xcrun devicectl`: list, pair, install, launch, terminate, screenshot, log capture.
- **LLDB Debugging** — Attach to simulator or device processes, set breakpoints, inspect variables, step through code.
- **UI Automation** — Tap, swipe, type, drag, pinch, and inspect accessibility trees on simulators (via IDB or CGEvent fallback).
- **Multi-platform** — tvOS, watchOS, visionOS build/run/test/discover targets.
- **Swift Package Manager** — Build, test, run, clean, resolve, dump, and init Swift packages.
- **Project Discovery** — Query the Bazel build graph, discover targets, inspect dependencies.
- **Scaffolding** — Generate new Bazel projects from templates (ios_app, macos_app, etc.).
- **Session & Config** — Workspace management, build profiles, defaults, health checks.
- **Background Daemon** — Per-workspace daemon for stateful operations.
- **Self-update** — Check for and install updates.
