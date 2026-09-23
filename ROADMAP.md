# Roadmap

_Refreshed September 23, 2026. Plans, not promises: priorities can shift with user feedback._

- Next release: v2.8.0, "Legacy Mac Reliability".
  - GitHub Releases update checker with explicit opt-in, version comparison, and link-only install flow. The code already has a TODO for this after Sparkle removal.
  - First-class MacPorts distribution and docs; retain Homebrew as secondary during its remaining Intel window.
  - Replace deprecated privileged-execution fallback with one reviewed, deterministic helper installation path; add daemon install/status/uninstall diagnostics.
  - Add exportable diagnostics: Mac model, macOS/OCLP versions, fan count/current/min/max RPM, daemon status, and recent helper logs, with privacy-safe defaults.
  - Regression tests for AC/battery changes, sleep/wake, multi-fan sync, boot daemon settings sync, and no-fan exit.
  - Translation work remains community/native-speaker only. Issue #13 should be updated to reflect completed Swedish/Turkish/Simplified Chinese/Korean/Hungarian contributions and list only languages still needing review. Do not fabricate translations.
- Next after 2.8: model database updates and a user-submitted hardware compatibility matrix.

Feature requests and bug reports: https://github.com/wolffcatskyy/smcFanControl/issues
