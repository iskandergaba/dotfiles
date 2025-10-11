# Dotfiles

This repository keeps track of dotfiles managed by [GNU Stow](https://www.gnu.org/software/stow/manual/stow.html).

## Usage

### Stow Packages
- To stow all packages:
```sh
stow */
```
- To stow a specific package, such as `bash`:
```sh
stow bash
```

### Unstow Packages
- To unstow all packages:
```sh
stow -D */
```
- To unstow a specific package, such as `bash`:
```sh
stow -D bash
```

### Restow Packages
- To restow all packages:
```sh
stow -R */
```
- To restow a specific package, such as `bash`:
```sh
stow -R bash
```