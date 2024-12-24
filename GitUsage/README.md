## 配置及上传

在自己电脑里找到自己所要上传的文件夹，右键Git Bash here

```
git init
```

之后输入

```
git remote add origin git@github.com:你的账户/你的仓库名称.git
```

将两边同步

```
git pull --rebase origin master
git pull origin master
```

```
git add .
git commit -m '注释信息'
git push origin master
```



## 删除本地文件

先输入命令查看

```
ls -l
```

在删除

```
rm -rf 前一个命令列出的文件名
```

