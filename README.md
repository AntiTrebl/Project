## New git repo

### Config git
```bash
$ git config --global user.name "user_name"
$ git config --global user.email "user_email"
$ git config --global core.autocrlf false
$ git config --global core.safecrlf true
$ git config --global credential.helper manager
```

### First start
```bash
$ git init
$ git add your_file
$ git commit -m "first commit"
$ git remote add remote_name https://github.com/you_repository/you_project
$ git push remote_name master
```

### Remove remote
```bash
$ git remote -v
$ git remote rm remote_name
```

### Remove a file from repo
```bash
$ git rm --cached file_name
```

### Remove directory from repo
```bash
$ git rm --cached -r dir_name
```

### Reset all commits from repo
Delete **.git** directory
```bash
$ git init
$ git add .
$ git commit -m "Initial commit"
$ git remote add origin https://github.com/you_repository/you_project
$ git push -f origin master
```
