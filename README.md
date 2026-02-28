# homebrew-vibeutils

Homebrew tap for [vibeutils](https://github.com/kelp/vibeutils) —
modern Unix utilities with colors, icons, and progress bars.

## Install

```bash
brew tap kelp/vibeutils
brew install vibeutils
```

## Usage

Commands are installed with a `v` prefix (`vls`, `vcp`, `vmv`,
etc.). To use without prefix, add vibebin to your PATH:

```bash
export PATH="$(brew --prefix)/opt/vibeutils/libexec/vibebin:$PATH"
```
