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
$ git commit -m"comments"
```

Save files with comments.

```shell
$ git log
```

Show all commits in this folder.

\$ git checkout -b dev

Create and go to the new branch 'fev'.

\$ git log --graph --decorate --all

Watch all commits

$ git log --graph --decorate $(git rev-list -g --all)

show all commits, include detouched.

$ git remote add origin https://github.com/NataliaKalacheva/demogit.git
$ git push -u origin master

\$ git remote -v

Show our remote

<<<<<<< HEAD
git ignore:
node_modules
package.log
buiche

\$ ssh-keygen

# Generate ssh key

\$ git pull origin dev

get updates from remote repository origin branch dev

<<<<<<< HEAD
\$ ssh-keyscan -t rsa github.com >> ~/.ssh/known_hosts
=======

> > > > > > > dfa1a159bb57824e46447a4999dba28e5da74d5d
> > > > > > > dev
