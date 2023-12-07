# Git subtree vs submodule


## subtree


```
git subtree add --prefix hello_subtree git@github.com:LimHyungTae/hello_subtree.git master
```

## submodule

```
git submodule add git@github.com:LimHyungTae/hello_subtree.git hello_submodule
git submodule init
git submodule update
git submodule update --remote
```



