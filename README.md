# co-author-git-logs

Pretty formatting for git logs with github's co-author support

Compatible with git-switch-electron see https://github.com/pluralsight/git-switch-electron

## Usage


### The HARD way

1. Run the prettyLogs.sh from your git directory

### The EASY way

1. Add a git alias (or a regular one)
 
```git config --global alias.lc '! ~/dev/co-author-git-logs/prettyLogs.sh'```


## Fomatted Output
`<ABBREVIATED_COMMIT_HASH> <RELATIVE_DATE> - <REF_NAMES> <SUBJECT> <AUTHOR> <CO_AUTHORS>`

On a current git branch named 'spike/logging'

```
ac1ea4f1 (3 days ago) - (HEAD -> spike/logging) Sweet git summary here <Zach Lintz> (Foo Bar, John Doe)
05f6799c (3 days ago) - Merge branch 'spike/loggingDemo' into spike/logging <Zach Lintz> 
```
