# Changelog

All notable changes to this deployment definition are documented in this file.
The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).

## [Unreleased]

### Added

- README with service description, configuration reference and quick start.

## [0.0.1]

### Added

- Initial App-as-Code service definition for Apt-Cacher NG (image `sameersbn/apt-cacher-ng:3.7.4-20220421`).
- HTTP proxy on port 3142 with a persistent package cache volume.
- Traefik routing and automatic DNS entry for the service.
