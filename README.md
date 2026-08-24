# Homebrew tap for Pipeline Island

[Pipeline Island](https://github.com/Uudg/pipeline-island) — GitLab CI pipelines,
live in the macOS notch.

```bash
brew install --cask Uudg/tap/pipeline-island
```

The cask builds from source on your machine rather than downloading a binary.
That's deliberate: signing an app for distribution needs a paid Apple Developer
ID, and without one a downloaded build gets blocked by Gatekeeper. Something you
compiled yourself is never quarantined.

You'll need a Swift toolchain — `xcode-select --install` if you don't have one.
