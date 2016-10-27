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
        treeo = log --oneline --decorate --all --graph
        treea = log --graph --pretty=short --decorate --branches --all
        treemea = log --graph --pretty=short --decorate --branches
        treemeadv = log --graph --format='%C(cyan) %p %Cred %h %C(white) %s %C(cyan) <%an>%C(bold yellow)%d%Creset'
        treeadv = log --graph --format='%C(cyan) %p %Cred %h %C(white) %s %C(cyan) <%an>%C(bold yellow)%d%Creset'
```

