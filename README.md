# naoj-open

Mini tool for macOS to connect naoj-open with the weekly key.

## Usage

`$ naoj-open xxxx-yyyy-zzzz`

The tool tries to remove naoj-open if it is already in the preferred networks
and then connect naoj-open (trial is repeated 5 times).
You may be asked to enter your account's password
to allow the tool to use `networksetup` (macOS builtin command).

## Installation

### Homebrew

```bash
brew tap snoopython/macos
brew install naoj-open

```

### Download ZIP

You can also download a ZIP and use bin/naoj-open as you like! 

## Requirements

naoj-open requires mac OS or OS X with Xcode or Command Line Tools installed.