# Neil's Gitconfig Scribblings

## Files (to be created)

`~/.gitconfig` should be created with minimally the following contents:
```
# vi:filetype=gitconfig
[include]
   path = [Path to dev/config-global in the git-aliases repository. E.g /Users/habiblawal/GitHub/git-aliases/dev/config-global]
[core]
    excludesFile = [Path to dev/ignore-global in the git-aliases repository. E.g /Users/habiblawal/GitHub/git-aliases/dev/ignore-global]
[user]
    name = [Your name]
    email = [Your github email address]
```

Other settings (from the global config file above) can also be overridden in this file.
