Cloning a repository that contains submodules

```
git clone --recursive [URL of the Git repo]
```

If already have a cloned repository

```
git submodule update --init --recursive
```

Pull all changes in repo including changes in the submodule

```
git pull --recurse-submodules
```


document reference link

https://www.vogella.com/tutorials/GitSubmodules/article.html