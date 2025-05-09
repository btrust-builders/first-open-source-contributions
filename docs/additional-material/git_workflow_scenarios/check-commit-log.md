# Check commit log

In order to check commits log for a branch, or, a file, following command can be used:

`git log [options] [path]`

The output of this command is given in reverse chronological order by default.

## Command output example
```
$ git log
commit e3fabb30ab536bd5876461d8a749301a321e714f (HEAD -> check-commit-log-ko, upstream/main, origin/main, origin/HEAD, main)
Author: Kelvin Isievwore <kelvinator4leo@mail.com>
Date:   Tue Jun 4 01:07:25 2024 -0400

    Add Kelvin Isievwore to Contributors list (#84962)

commit 4af4ec8a56e057ce8768af77eda528453974d0bc
Author: Geeky Kel <168693312+geekykel@users.noreply.github.com>
Date:   Mon Jun 3 23:06:05 2024 -0600

    Add Geeky Kel to Contributors list (#84961)
```


## Command variations and options 
- In order to perform the commits reachable from a particular commit ids: <i>(In this case, `foo` and `bar`)</i><br>
    `git log foo bar ` 
- It is also possible to remove the commits reachable from a given commit id by adding a `^` in front of commit id: <i>(In this case, `baz`)</i><br>
    `git log foo bar ^baz`
- Commit log for a particular file: <br> 
    `git log --all <filename>`
- Limit number of commits in log: <i>(In this case, `5`)</i><br> 
    `git log -n 5`

## Refer
- [Official documentation](https://git-scm.com/docs/git-log)
