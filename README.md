# Kieran Murphy’s dotfiles

My dotfiles, really created as my first experiment into GitHub.  

## Installation

Clone the repository into your home directory or anywhere else for that matter.

```bash
git clone https://github.com/kieranjmurphy/.dotfiles.git
```

Remove the file and create the symlink you would like to use.

```bash
mv .bash_profile .dotfiles/bash_profile
ln -s .dotfiles/bash_profile .bash_profile
```

There is an included 'relocate.sh' which will carry out the two steps above. The usage is as follows 

```bash
./relocate.sh bash_profile
```

Not fully tested so please excuse any errors.

## Feedback

Suggestions/improvements
[welcome](https://github.com/kieranjmurphy/.dotfiles/issues)!

## Thanks to…

* [Mathias Bynens](https://github.com/mathiasbynens) for sharing his [bootstrap](https://github.com/mathiasbynens/dotfiles) and getting me started with dotfiles.