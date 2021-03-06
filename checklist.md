## Class Checklist for Students

Here's your checklist for the *Git-under-the-Hood workshop*. If you want a discursive list, with explanations,
[it's here](https://docs.google.com/document/d/1eQr6fFiZPGYNc2DSWdA1s5fS0nU5midRgpaZBttD49E/edit?usp=sharing).

If you think something's missing, or you can say something better, don't just be a 
קיביצער
: fork this repo, make your fix, and issue a pull request.

- The computer you'll bring

  + bring up a terminal window running bash/dash/zsh/ksh and type basic, shell commands

  + `uname -a` says you have Linux or some other Unix-flavored OS.

  + **tree(1)** and **sha1sum(1)** are installed

  ```bash
  tree
  sha1sum /etc/passwd
  ```

  + use a programming editor (vi, emacs, gedit, atom, ...) to write and run a simple shell script

  ```bash
  $ cat hello
  #!/bin/bash -eux
  echo hello, world
  $ ./hello
  hello, world
  ```

- git

  + `git version` shows >= 1.9.1

  + you have colorized git output

  ```bash
  git config --global ui.color auto
  git log
  ```

  + you have the alias `git lol`

  ```bash
  git config --global alias.lol 'log --graph --decorate --oneline --all'
  ```

- GitHub

  + clone some repos


  ```bash
  git clone https://github.com/jsh/git-under-the-hood
  git clone https://github.com/jsh/git-scratch
  cd git-scratch
  sudo make install
  ```

  + create a repo on GitHub

  + push to the repo from the machine you'll use

- Networking

  + `ssh/` is set up so ***you are not prompted for a password*** for this command:

  ```bash
  ssh localhost
  ```

- Overheads

  + install Flash to see them on your own computer. Go to Prezi.com and watch any presentation to verify.
  + [Jeff Haemer at Prezi](https://prezi.com/user/lmn5jzymwcrh/)
