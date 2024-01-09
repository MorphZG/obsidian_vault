---
tags: [stow, dotfiles, linux]
---

GNU stow manual
[gnu.org](https://www.gnu.org/software/stow/manual/)

Jake Wiesler
Manage your dotfiles like a superhero
[youtube.com/video](https://www.youtube.com/watch?v=FHuwzbpTTo0)
[jakewiesler.com/blogpost](https://www.jakewiesler.com/blog/managing-dotfiles)

DevInsideYou
Sync your .dotfiles with git and GNU Stow like a pro
[youtube.com/video](https://www.youtube.com/watch?v=CFzEuBGPPPg)

### Understanding stow

Few important concepts to understand. Can find them in Terminology documentation.  
- a package is a folder containing related dotfiles. (vim, bash, git...)
- a stow directory is a folder containing one or more packages.
- target directory is the location in which a package's contents will be symlinked.

This is how it looks in practice:
```sh
target-directory
    stow-directory
        package-1
            .dotfile1
        package-2
            .dotfile2
            .dotfile3

$HOME           --->    (target-directory)
    dotfiles    --->    (stow-directory)
        bash    --->    (package)
            .bashrc     (dotfile)
            .bash_aliases
        git
            .gitconfig
```


