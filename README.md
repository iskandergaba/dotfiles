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
stow --delete */
```

- To unstow a specific package, such as `bash`:

```sh
stow --delete bash
```

### Restow Packages

- To restow all packages:

```sh
stow --restow */
```

- To restow a specific package, such as `bash`:

```sh
stow --restow bash
```
