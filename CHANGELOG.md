# Changelog

All notable changes to this project will be documented in this file.

## [1.0.0] - 2026-05-05

### Added
- Created `core/` folder for fundamental rules (Master Rules, Execution Gate, Minimal Change Policy).
- Created `profiles/` folder for specific AI modes (Vibe Coding, Debug, Refactoring, Architecture, AI Training, Edge Deployment, Control System, Documentation).
- Created `recipes/` folder for quick combinations of prompts.
- Created `examples/` folder to demonstrate real-world usage.
- Created `tool-specific/` folder for Cursor and other AI IDE rules.
- Added `PROMPT_INDEX.md` to help users choose the right prompt.
- Added conflict handling rules to `01_master_rules.md`.
- Added Vibe Coding rhythm to `vibe_coding.md`.
- Added refactoring levels to `refactor_review.md`.
- Added diagnosis evidence levels to `debug_diagnosis.md`.
- Added task branches to `algorithm_ai.md`.
- Fixed markdown single-line formatting issues for better readability and git diffs.

### Changed
- Major repository restructuring from flat files to a scalable framework.
- Enhanced README.md to serve as a product landing page.

### Removed
- Removed flat `01_master_rules.md` to `09_prompt_profiles.md` structure in favor of the new categorized directories.
