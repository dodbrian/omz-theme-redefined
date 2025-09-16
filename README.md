# Redefined Theme for Oh My Zsh

A clean and elegant theme for Oh My Zsh.

## Features

*   The current git branch color is now light green for better readability.
*   The elapsed time shown after the command finished is displayed in a human-readable format.

## Installation

### Easy Install

You can install the theme by downloading the theme file directly into your Oh My Zsh custom themes directory.

Using `curl`:
```bash
curl -o ~/.oh-my-zsh/custom/themes/redefined.zsh-theme https://raw.githubusercontent.com/dodbrian/omz-theme-redefined/main/redefined.zsh-theme
```

Or using `wget`:
```bash
wget -O ~/.oh-my-zsh/custom/themes/redefined.zsh-theme https://raw.githubusercontent.com/dodbrian/omz-theme-redefined/main/redefined.zsh-theme
```

### Manual Install (for developers)

If you want to keep the repository for development or easy updates, you can clone it and symlink the theme file.

1.  Clone this repository into your Oh My Zsh custom themes directory:

    ```bash
    git clone https://github.com/dodbrian/omz-theme-redefined.git ~/.oh-my-zsh/custom/themes/omz-theme-redefined
    ```

2.  Symlink the theme file to your Oh My Zsh custom themes directory:

    ```bash
    ln -s ~/.oh-my-zsh/custom/themes/omz-theme-redefined/redefined.zsh-theme ~/.oh-my-zsh/custom/themes/redefined.zsh-theme
    ```

## Usage

### With the `omz` command

1.  Set the theme:
    ```bash
    omz theme set redefined
    ```

2.  Reload the shell:
    ```bash
    omz reload
    ```

### Manually

1.  Set `ZSH_THEME="redefined"` in your `~/.zshrc` file.

2.  Reload your shell:
    ```bash
    source ~/.zshrc
    ```

## Screenshots

*(Coming soon)*

## Credits

This theme is based on the `refined` theme from Oh My Zsh, which was adapted by [mcornella](https://github.com/mcornella). The `refined` theme itself was a port of the `pure` theme, originally created by [sindresorhus](https://github.com/sindresorhus).
