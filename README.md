# Version System Test Repository

This repository is used to test the [version-system GitHub Action](https://github.com/sanjeevkumarraob/version-system) functionality.

## Test Coverage

This repository contains comprehensive tests for:

- ✅ **Basic Versioning**: Simple semantic versioning without prefixes or suffixes
- ✅ **Prefix Versioning**: Versions with prefixes like `dev-1.0.0`, `staging-1.0.0`
- ✅ **Suffix Versioning**: Versions with suffixes like `1.0.0-alpha`, `1.0.0-beta`
- ✅ **Module Versioning**: Module-specific versions like `api-2.1.0`, `frontend-1.5.0`
- ✅ **Release Creation**: Automated GitHub release creation with proper version tags

## Repository Structure

```
.
├── version.txt                    # Main version file
├── modules/                       # Module-specific versions
│   ├── api/version.txt           # API module version
│   ├── frontend/version.txt      # Frontend module version
│   └── backend/version.txt       # Backend module version
└── .github/workflows/            # Test workflows
    ├── test-basic.yml            # Basic versioning tests
    ├── test-prefix.yml           # Prefix versioning tests
    ├── test-suffix.yml           # Suffix versioning tests
    ├── test-module.yml           # Module versioning tests
    └── test-release.yml          # Release creation tests
```

## Test Results

All tests are passing successfully, validating the core functionality of the version-system action before marketplace publication.
