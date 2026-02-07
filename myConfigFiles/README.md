# Chezmoi
# New Machine:
## Chezmoi
- `sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply https://github.com/phamousq/dotfiles.git`

## Homebrew
- make/update brewfile with:
  - `brew bundle dump --file=~/.local/share/chezmoi/Brewfile --force`
- install brewfile with:
- `brew bundle install --file=~/.local/share/chezmoi/Brewfile`
  - you'll have to sit by and enter your password occasionally bc there are some programs that need admin access
    - can't use sudo because it's not secure

# Usage
- navigate to dotfiles:
  - `cm cd`
- adding a file to be tracked:
  - `cm add <filename>`
- on an existing machine, run 
  - `chezmoi update`

# Todo:
- remove yabai and skhd
- implement [symlinking](https://www.chezmoi.io/user-guide/manage-different-types-of-file/#handle-configuration-files-which-are-externally-modified) for certain files