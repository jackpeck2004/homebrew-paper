# Paper Homebrew tap

Install [Paper](https://github.com/jackpeck2004/paper-pdf), the free native macOS PDF editor:

```sh
brew install --cask jackpeck2004/paper/paper-pdf
```

Or tap explicitly:

```sh
brew tap jackpeck2004/paper
brew install --cask paper-pdf
```

Requires macOS 14 Sonoma or later. The release ZIP includes Apple Silicon and Intel binaries and is verified by SHA-256.

The current development build is ad-hoc signed and not notarized. macOS may require your approval in System Settings → Privacy & Security before first launch. This cask does not remove quarantine or disable Gatekeeper.

Paper-authored source is MIT licensed; its bundled MuPDF engine retains AGPL distribution requirements. Complete source is included with every binary release. The cask itself is MIT licensed.

Uninstall with `brew uninstall --cask paper-pdf`. Saved signatures and recovery data are deliberately preserved.
