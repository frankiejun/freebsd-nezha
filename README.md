# FreeBSD-nezha

This repository contains FreeBSD builds for the Nezha dashboard application.

## Build Status

![Build FreeBSD Dashboard](https://github.com/frankiejun/freebsd-app/actions/workflows/build-freebsd.yml/badge.svg)

## FreeBSD Dashboard Binary

This repository automatically builds the FreeBSD version of the Nezha dashboard binary. The build process is triggered when:

1. A new version of Nezha is released
2. Manual trigger through GitHub Actions
3. Push to main branch
4. Pull request to main branch

The FreeBSD binary can be found in the [Releases](../../releases) section, with the same version tag as the corresponding Nezha release.

### Build Process
- The build runs daily at 00:01 UTC
- Checks for new Nezha releases
- If a new version is detected, builds the FreeBSD binary
- Creates a new release with the binary attached

### Download
You can download the latest FreeBSD binary from the [Latest Release](../../releases/latest) page.
