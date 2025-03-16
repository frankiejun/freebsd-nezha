# FreeBSD App

This repository contains FreeBSD builds for the Nezha dashboard application.

## Automated Builds

This repository uses GitHub Actions to automatically build the Nezha dashboard for FreeBSD. The workflow:

1. Sets up a FreeBSD virtual machine
2. Installs required dependencies (Go, swag)
3. Builds the dashboard from source
4. Packages the binary and commits it to the repository

## Latest Build

The latest FreeBSD build can be found in the `dashboard.gz` file in the root of this repository.

## Build Status

![Build FreeBSD Dashboard](https://github.com/frankiejun/freebsd-app/actions/workflows/build-freebsd.yml/badge.svg)
