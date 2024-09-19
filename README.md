# Customisation for oh-my-zsh

[Oh-my-zsh][] supports custom functions, completions, etc. in a default directory `.oh-my-zsh/custom`.

To get this under version control, I added `export ZSH_CUSTOM="$HOME/.config/tastapod/omz_custom"` in my [.zshenv][] file.

To use this alongside my [dotfiles][] setup, run `git clone https://github.com/tastapod/omz_custom ~/.config/tastapod/omz_custom` and it will Just Work&trade;.

[Oh-my-zsh]: https://ohmyz.sh/
[.zshenv]: https://github.com/tastapod/dotfiles/blob/main/zshenv#L5
[dotfiles]: https://github.com/tastapod/dotfiles/
