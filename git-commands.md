```shell
$ cd ..
```

```shell
$ cd git-clone/
```

GitHub have database, working tree, and stage area.

Working tree - our working space where we make our files

=> from this space we add ( git add .) our files in Stage Area

=> git commit to save from SA to database.

In Database we have 3 folders for each change(info about commit, working tree).
In working tree have information about changing and link to files(name of cache).

```shell
$ git init
```

Initialized repository

```shell
$ git status
```

Check status. Usually On branch master.

```shell
 $ git add .
```

Watch all doc in folder. Add docs to working tree.

```shell
$ git cat-file -p 9d1234
```

Print object's content. 9d - name folder, 1234-first symbols of cache.

```shell
$ git commit -m "comments"
```

Save files with comments.

```shell
$ git log
```

Show all commits in this folder.

```shell
$ git checkout -b dev
```

Create and go to the new branch 'fev'.

```shell
$ git log --graph --decorate --all
```

Watch all commits

```shell
$ git log --graph --decorate $(git rev-list -g --all)
```

show all commits, include detouched.

```shell
$ git remote add origin https://demolink.cc
```

connect with remote

```shell
$ git push -u origin master
```

push in remote branch master

```shell
$ git remote -v
```

Show our remote

```shell
$ ssh-keygen
```

Generate ssh key

```shell
$ git pull origin dev
```

get updates from remote repository origin branch dev

```shell
$ ssh-keyscan -t rsa github.com >> ~/.ssh/known_hosts
```
