# alma-ohmyzsh-theme

Simple, informative and good looking theme for zsh.

Based on theme made by [RougarouTheme/rougarou-zsh](https://github.com/RougarouTheme/rougarou-zsh).

I wanted to use an agnoster-like theme, but I couldn't find one that fitted to my needs. These are the requirements I wanted:
  - Not just simple text, but an "agnoster-like look".
  - Use of icons to increase readability.
  - Ability to show full working path.
  - Cursor always stays at the same point when a new prompt comes out.

## Screenshots

### Main look
<p align="center">
  <img alt="alma-theme" width="400" src="./images/alma-theme.png">
</p>

### Shows git status
<p align="center">
  <img alt="alma-theme-git" width="400" src="./images/alma-git.png">
</p>

### Alert if the previous command fails
<p align="center">
  <img alt="alma-theme-error" width="400" src="./images/alma-error.png">
</p>

## Install

1. Install a [Nerd Font](https://www.nerdfonts.com/)! The theme uses Nerd Font Icons.
2. Copy the `alma.zsh-theme` file into `~/.oh-my-zsh/custom/themes/` folder.
3. Update your `.zshrc` file like so:
  ```
  ZSH_THEME="alma"
  ```
4. Source the `.zshrc` file or restart the terminal: `source ~/.zshrc`

## Tweaks Made
