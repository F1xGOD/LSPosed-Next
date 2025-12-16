🎉 Introducing LSPosed Next v2.0.0-next

This fork refreshes LSPosed for newer Android releases and KernelSU Next while keeping the framework compatible with existing modules.

### ✨ What's New
*   Rebranded to **LSPosed Next** with author set to **F1xGOD** and a bumped major version/code base (2.x, code ≥ 22999).
*   Build toolchain aligned with Android 16/17 (SDK/NDK 36) to keep pace with new platform changes.
*   KernelSU Next (version code 20000+) detection during install to avoid outdated-environment errors.
*   OTA/update endpoints now point to this repository with renamed artifacts (`LSPosed-Next-…`).

### 🐛 Fixes
*   Addressed Shamiko environment errors on KernelSU Next by properly recognising newer KSU builds.
*   Improved module path detection for non-Magisk installs to avoid missing-module checks.

### 🔗 Links
*   Troubleshooting guide: https://github.com/F1xGOD/LSPosed-Next/issues/123
*   Discussion: https://github.com/F1xGOD/LSPosed-Next/discussions
