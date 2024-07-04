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

The repository currently includes the following configuration files:

- `.zshrc` - Configuration file for zsh
- `RStudio` settings
  - `rstudio-prefs.json` - Preferences for RStudio
- `VSCode` settings
  - `settings.json` - User settings for VSCode
  - `keybindings.json` - Custom keybindings for VSCode

## Installation

1. **Clone the repository:**

   ```sh
   git clone https://github.com/yourusername/dotfiles.git
   cd dotfiles
   ```

2. **Set up symlinks:**

# For zsh
```
ln -s $(pwd)/.zshrc ~/.zshrc
```

# For RStudio
```
mkdir -p ~/.config/rstudio
ln -s $(pwd)/rstudio-prefs.json ~/.config/rstudio/rstudio-prefs.json
```

# For VSCode
```
mkdir -p ~/.config/Code/User
ln -s $(pwd)/vscode/settings.json ~/.config/Code/User/settings.json
ln -s $(pwd)/vscode/keybindings.json ~/.config/Code/User/keybindings.json
```

3. ***Restart your applications to apply the new settings***.