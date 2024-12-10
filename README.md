# Chezmoi
- sh -c "$(curl -fsLS get.chezmoi.io)" -- init --apply Phamousq
- on an existing machine, run `chezmoi apply`
- cm update when working on a new machine

- adding a file to be tracked:
  - cm add <filename>


- todo
  - remove yabai and skhd
  - implement [symlinking](https://www.chezmoi.io/user-guide/manage-different-types-of-file/#handle-configuration-files-which-are-externally-modified) for certain files