submoduleを追加する

```
git submodule add https://github.com/libsdl-org/SDL
```

submoduleを特定のタグに
```
cd SDL
git pull
git checkout release-3.2.20
```

submoduleも再帰的にcloneする

```
git clone --recurse-submodules 
```
