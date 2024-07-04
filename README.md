# My Dotfiles Repository

This repository contains my personal configuration files (dotfiles) for various development tools. Currently, it includes configurations for RStudio, VSCode, and `zshrc`. 

## Table of Contents

- [Getting Started](#getting-started)
- [Contents](#contents)
- [Installation](#installation)
- [Customization](#customization)
- [Contributing](#contributing)
- [License](#license)

## Getting Started

To get started with these dotfiles, you can clone the repository to your local machine and set up the symlinks to use these configurations.

### Prerequisites

- `git` installed on your machine
- Basic knowledge of shell commands
- Tools installed for the configurations you will be using (e.g., RStudio, VSCode, zsh)

## Contents

The repository currently includes the following directories:

- `zsh` -   zsh shell config files
  - `.zshrc` - Configuration file for zsh
- `RStudio` - RStudio config files 
  - `rstudio-prefs.json` - Preferences for RStudio
  - `.Rprofile` - RStudio start-up file 
- `VSCode` - VSCode config files
  - `settings.json` - User settings for VSCode
  - `keybindings.json` - Custom keybindings for VSCode

## Installation

**Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/dotfiles.git
   cd dotfiles
   ```

## Copy the configuration files

### zsh
```
cp .zshrc ~/.zshrc
```

### RStudio
```
mkdir -p ~/.config/rstudio
cp rstudio-prefs.json ~/.config/rstudio/rstudio-prefs.json
```

### VSCode
```
mkdir -p ~/.config/Code/User
cp vscode/settings.json ~/.config/Code/User/settings.json
cp vscode/keybindings.json ~/.config/Code/User/keybindings.json
```

*** *You may need to restart your applications to apply the new settings* ***.