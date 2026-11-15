
# Changelog

All notable changes to CodeMap will be documented in this file.

This project follows [Semantic Versioning](https://semver.org/).

## [1.1.0] - 2026-11-15

### Added

### Python Dependency Support

- Python project-local import resolution.
- Python standard-library module recognition.
- Automatic third-party dependency recognition through supported dependency manifests.
- Support for "requirements.txt", "pyproject.toml", "Pipfile", "Pipfile.lock", and "setup.cfg".
- Manual registration of third-party Python modules through CodeMap Settings.
- Ability to add and remove registered Python external modules.
- Automatic recognition of registered external modules during dependency analysis.
- Python import classification into internal, external, standard-library, and unresolved dependencies.

### Settings and Configuration

- Persistent storage for manually registered Python external modules.
- Empty-by-default Python external module registration list.
- Apply and rescan functionality for Python external module settings.
- Synchronization of Python external module settings with the import resolver.

### Improved

- Python dependency resolution through configurable external module recognition.
- Settings management for Python dependency analysis.
- Workspace rescanning when Python external module settings are updated.

## [1.0.0] - 2026-11-14

### Added

#### Workspace Management
- Workspace detection and project folder selection.
- Workspace scanning and file indexing.
- Workspace file watching and change tracking.
- Workspace status indicators.
- Project structure exploration.

#### Dependency Analysis
- Dependency graph generation.
- Import and export relationship analysis.
- Internal and external dependency tracking.
- Unresolved import detection.
- Dependency graph visualization.
- Dependency graph filtering and node limits.
- Dependency path exploration.

#### Architecture Analysis
- Architecture structure detection.
- Architecture boundary analysis.
- Architecture boundary rules and management.
- Architecture comparison between snapshots.
- Cross-folder dependency analysis.
- Dependency cycle detection.
- Dependency bottleneck analysis.
- Dependency clustering and depth analysis.
- Coupling and stability analysis.
- Impact analysis.

#### Codebase Health
- Codebase health analysis.
- Duplicate import detection.
- Orphan file detection.
- Unresolved import analysis.
- Codebase health reporting and export.

#### Snapshot Management
- Architecture snapshot creation.
- Local snapshot storage.
- Snapshot comparison.
- Structural change reporting.
- Architecture comparison reports.

#### User Interface
- Overview dashboard.
- Workspace explorer.
- Dependency visualization view.
- Architecture analysis view.
- Snapshot comparison view.
- Settings view.
- Configurable graph display settings.
- Node statistics.
- Responsive navigation.
- Dark-themed interface.

#### Developer Experience
- Modular application architecture.
- Centralized event management.
- Workspace and filesystem adapters.
- Parser registry and parser services.
- JavaScript and TypeScript parser support.
- Import resolution system.
- Structured error handling and logging.

### Notes
- Initial public development release.
- Designed as a visual project intelligence plugin for Acode.
- Additional improvements, language support, and refinements are planned.
