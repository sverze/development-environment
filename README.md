# Development Environment

Contains helpful configuration files for Linux and macOS development environments:

## Bash Configuration
- Bash profile and configuration files for Linux and macOS

## iTerm2 Configuration
- Custom color schemes for iTerm2 (Brogrammer, FieldsOfGold, Homebrew)

## Zsh Configuration
- Custom .zshrc with extensive aliases and functions
- Integrated with Oh My Zsh framework
  - Uses the "agnoster" theme
  - Configured with git plugin
  - Requires Oh My Zsh to be installed at `$HOME/.oh-my-zsh`

## Features
- Comprehensive aliases for file management, networking, and system operations
- Custom functions for common development tasks
- Organized sections for different types of operations
- Support for API keys through separate configuration file

## Installation
To use these configurations, clone this repository and symlink the desired configuration files to your home directory.

### Oh My Zsh Dependency
The zsh configuration requires [Oh My Zsh](https://ohmyz.sh/) to be installed. Install it with:
```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```
