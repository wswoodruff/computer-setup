### List existing
```bash
git config --list
# Example output
credential.helper=osxkeychain
user.name=doggyjones
user.email=doggyjones@gimmeurbones.com
alias.s=status
alias.c=commit
alias.a=add --all .
```

### Identity
```bash
$ git config --global user.name "Doggy Jones"
$ git config --global user.email doggyjones@gimmeurbones.com
```

### U know u wanna use `git s`

```bash
$ git config --global alias.s status
$ git config --global alias.c commit
$ git config --global alias.a "add --all ."
```
