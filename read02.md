 summary of review

# Remote Repositories

In order to collaborate on Git projects, you must interact with remote repositories, versions of *a project residing online* or on a network. You can work with multiple repositories, for which you can have read/write or read-only privileges. Teams can use remote** repositories to push information to and pull data from.**

By running the ```git remote``` command, you can view the short names, such as “origin,” of all specified remote handles.

By using ```git remote -v```, you can view all the remote URLs next to their corresponding short names

#### for example
```
$ cd example

$ git remote -v

remote1 https://github.com/remote1/example (fetch)

remote1 https://github.com/remote1/example (push)

remote2 https://github.com/remote2/example (fetch)

remote2 https://github.com/remote2/example (push)

remote3 https://github.com/remote3/example (fetch)

remote3 https://github.com/remote3/example (push)
```


