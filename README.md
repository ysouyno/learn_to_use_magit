# learn_to_use_magit

## add/commit/push

``` shell
git add .
git commit -m "commit"
git push origin master
```

## branch

``` shell
git checkout -b dev
git add .
git commit -m "dev"
git push origin dev
```

## another branch base on master

``` shell
git checkout -b another_dev
git add .
git commit -m "another dev"
git push origin another_dev
```

## 简短操作说明

### `diff`操作

`C-x g`进入`magit`，`d`打开`diff`选项，`u`与`unstaged`比较，`s`与`staged`比较。

平时我用的`git diff`只能看到与`unstaged`的比较，所以`d`，`u`够用。

### `stage`操作

`C-x g`进入`magit`，`s`打开`stage`选项，选择要`stage`的文件回车即可。

### `commit`操作

`C-x g`进入`magit`，`c`打开`commit`选项，`c`输入日志`commit`。
