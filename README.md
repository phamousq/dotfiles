# Chezmoi
- running on a new machine:
  - `sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply https://github.com/phamousq/dotfiles.git`
  - `brew bundle install`
- on an existing machine, run 
  - `chezmoi update`

- adding a file to be tracked:
  - `cm add <filename>`


- todo
  - remove yabai and skhd
  - implement [symlinking](https://www.chezmoi.io/user-guide/manage-different-types-of-file/#handle-configuration-files-which-are-externally-modified) for certain files

# Brewfile 
- make brewfile with:
  - `brew bundle dump --file=~/.local/share/chezmoi/Brewfile --force`