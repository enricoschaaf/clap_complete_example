1. Run command for your shell

Bash

echo "source <(COMPLETE=bash your_program)" >> ~/.bashrc
Elvish

echo "eval (E:COMPLETE=elvish your_program | slurp)" >> ~/.elvish/rc.elv
Fish

echo "source (COMPLETE=fish your_program | psub)" >> ~/.config/fish/config.fish
Powershell

echo "COMPLETE=powershell your_program | Invoke-Expression" >> $PROFILE
Zsh

echo "source <(COMPLETE=zsh your_program)" >> ~/.zshrc

2. cargo install --path .

3. Try to get completions

Tested using cargo and rust nightly
