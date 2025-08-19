# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [0.2.7] - 2025-08-19

### Changed

- pinning the version of gql in the setup.py to 3.5.3 since 4.0 has breaking changes for now

## [0.2.6]- 2025-05-30

### Changed

- Updated the issue_task functionality to allow supplying `payload_type` name
  - This will enable features like `forge` where the backing payload type container differs from the type of the callback