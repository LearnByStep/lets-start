## 查看状态

没有副作用

```shell
git status
```

## 初始化仓库

```shell
git init
```

## 将文件添加到暂存区

```shell
git add [filename]
```

## 生成版本

```shell
git commit -m "版本的描述信息"
```

## git的配置操作

```shell
git config --global user.name jinweios
git config --glboal user.email jinwei.peng@outlook.com
```

## 查看版本信息

```shell
git log
```

## 添加远端仓库并提交

```shell
git remote add origin https://github.com/jinweios/lets-start.git

# 只有第一次会报错，我们需要使用报错的命令进行首次提交
git push -u origin master

## 以后仅需要 git push
git push
```

## 如何clone？
当本地没有远端仓库的代码时间，如何将远端仓库拉取到本地

```shell
git clone https://github.com/LearnByStep/lets-start.git
```
