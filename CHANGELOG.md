# Changelog
All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/), and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased
### Fixed
- Handle __future__ import to allow pipe-union syntax on 3.9

### Changed
- Update description

## 0.1.2 - 2025-07-11
### Fixed
- Specify versions of pyOpenSSL and vmware to play happily together

## 0.1.1 - 2025-05-22
### Fixed
- Handle required args by `Deployer.argparse_post` rather than `required=True` to allow value to come from config file

## 0.1.0 - 2025-05-20
### Added
- initial commit
