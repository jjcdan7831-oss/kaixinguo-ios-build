# Kaixinguo iOS build configuration

Builds the public upstream [Kaixinguo iOS 0.7.0](https://github.com/kadaliao/kaixinguo-ios/releases/tag/v0.7.0), pinned to commit `3788c09358374cc3c53bd04d70c335153b36e50c`.

The workflow uses GitHub's standard `xcode-27` runner with Xcode 27.1. It downloads upstream source, runs its existing core tests, builds only the iPhone/iPad application without signing, and produces an IPA, SHA-256 checksum, app metadata, and build logs.

No Apple account, signing certificate, device pairing record, phone backup, or personal application data is used by this workflow. Sign the output locally after reviewing the build. It does not run automatically on a schedule or publish releases. Build artifacts expire after one day.

This repository contains build configuration only. The application source retains the upstream MIT license and copyright. Successful compilation and archive checks do not establish playback availability, device compatibility, or an independent security audit.
