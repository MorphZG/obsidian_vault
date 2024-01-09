---
tags: tar linux
---

# Archives with Tar

```sh
tar -cvf backup.tar ~/Documents ~/Pictures ~/.dotfiles
```

tar command options:
-c create new archive
-r append files to archive
-v verbose, show progress
-f filename (name of archive)

```sh
tar -xvf backup.tar
```

-x extract
-t list the content of the archive