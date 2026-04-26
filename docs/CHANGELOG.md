# Changelog

## v4.1.0 - 2026-04-26

### Added
- GitHub Actions workflow to run a CLI smoke check and deploy the `ui/` site to GitHub Pages on pushes to `main`.
- Keyboard UX improvement: pressing Enter in either number input now runs a calculation.

### Fixed
- CLI now starts correctly when running `python src/smart_calculator.py` by using a proper `if __name__ == "__main__":` entrypoint.
- History loading now resets in-memory history before reading persisted entries.

## v4.0.0 - 2026-04-26

### Added
- Refreshed browser UI with improved layout and styling.
- UI history panel with localStorage persistence.
- Swap-input and clear-history actions in UI.
- Central `VERSION` file for repository-level versioning.

### Changed
- CLI now displays explicit version banner (`v4.0.0`).
- CLI history file path is now stable from repository root via `pathlib`.
- Documentation rewritten with complete setup and feature details.
