# commands
## Github config
### to add alias: 
```
git config --global alias.tree "{command}"
```
### to edit the global config:
```
git config --global -e
```
### my alias configs:
```
[alias]
        tree = log --graph --oneline --decorate --branches --all
        treeme = log --graph --oneline --decorate --branches
        treea = log --graph --pretty=short --decorate --branches --all
        treemea = log --graph --pretty=short --decorate --branches
        treeadv = log --all --graph --decorate --branches --format='%C(cyan) %p %Cred %h %C(white) %s %C(cyan) <%an>%C(bold yellow)%d%Creset'
        treemeadv = log --graph --decorate --branches --format='%C(cyan) %p %Cred %h %C(white) %s %C(cyan) <%an>%C(bold yellow)%d%Creset'
```

