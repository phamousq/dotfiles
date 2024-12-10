# Chezmoi
- `sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply phamousq`
- on an existing machine, run 
  - `chezmoi apply`
- `chezmoi update` when working on a new machine
- `brew bundle install`

- adding a file to be tracked:
  - cm add <filename>


- todo
  - remove yabai and skhd
  - implement [symlinking](https://www.chezmoi.io/user-guide/manage-different-types-of-file/#handle-configuration-files-which-are-externally-modified) for certain files