# Changelog

All notable changes to this project will be documented in this file.

## [2.0.0] - 2026-01-04

### What's Changed
- Add RGB support for APs that expose `led_override_color` and `led_override_color_brightness`
- Refactor `platformAccessory.ts`:
  - Store intended state
  - Separate communication from state management
- Add RGB / HSV conversion functions

## [1.4.5] - 2025-05-14

### What's Changed
- Patch: Add migration fallback for missing site property in cached accessories
- Ensures restored accessories from cache work correctly after multi-site support
- No longer logs "missing site information" errors for affected users

## [1.4.4] - 2025-05-14

### What's Changed
- Add multi-site support for UniFi OS and self-hosted controllers
- Improved device discovery and filtering
- Enhanced debug logging and error handling
