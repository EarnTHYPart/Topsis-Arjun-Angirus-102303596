# Release 0.1.1

## Summary
Packaging improvements and automated publish workflow added; version bumped to 0.1.1.

## Changes
- Version: Updated to 0.1.1 in setup.cfg.
- Metadata:
  - Updated `download_url` to v0.1.1 tag archive.
  - Added `project_urls` (Source, Issues).
  - Switched to `license_files = LICENSE.txt`.
- Build: Added pyproject.toml declaring setuptools build backend.
- Workflow: Added GitHub Actions workflow to publish on GitHub releases.
- Dependencies: Runtime deps remain numpy>=1.26.0 and pandas>=2.0.0.

## Artifacts
- Tag: v0.1.1
- Tarball: https://github.com/EarnTHYPart/Topsis-Arjun-Angirus-102303596/archive/refs/tags/v0.1.1.tar.gz
- PyPI (after publish): https://pypi.org/project/Topsis-Arjun-Angirus-102303596/0.1.1/

## Install
- From PyPI: `pip install Topsis-Arjun-Angirus-102303596`
- From source: `pip install .`

## CLI Usage
```bash
topsis-aaa-102303596 <InputDataFile> "0.5,0.3,0.2" "+,+,-" <OutputResultFile>
```

## Notes
- Ensure repo secret `PYPI_TOKEN` is set to a valid PyPI API token for GitHub Actions auto-publish.
