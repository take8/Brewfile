# Brewfile

Package list for [homebrew](http://brew.sh/).

Managed by [homebrew-file](https://github.com/rcmdnk/homebrew-file).

---

## How to create

- Install Homebrew

  ```sh
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  ```

- Create GitHub repository

- Set the repository

  ```sh
  brew file set_repo
  ```

- Initialize

  ```sh
  brew-file init
  ```

- Edit

  ```sh
  brew-file edit
  ```

- Update the repository

  ```sh
  brew file update
  ```

## How to use

- Install Homebrew

  ```sh
  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"
  ```

- Clone the repository

  ```sh
  brew file set_repo
  ```

- Install according to Brewfile

  ```sh
  brew file install
  ```
