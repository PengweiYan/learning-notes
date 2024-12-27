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
git pull --rebase origin main
git pull origin main
```

```
git add .
git commit -m '注释信息'
git push origin main
```

## 常用提交类型
| Type     | 类型 | 描述                                                   |
| -------- | ---- | ------------------------------------------------------ |
| feat     | 功能 | 新增 feature                                           |
| fix      | 修复 | 修复 bug                                               |
| docs     | 文档 | 仅仅修改了文档，比如 README, CHANGELOG, CONTRIBUTE等等 |
| style    | 格式 | 仅仅修改了空格、格式缩进、逗号等等，不改变代码逻辑     |
| refactor | 重构 | 代码重构，没有加新功能或者修复 bug                     |
| perf     | 优化 | 优化相关，比如提升性能、体验                           |
| test     | 测试 | 测试用例，包括单元测试、集成测试等                     |
| chore    | 回滚 | 改变构建流程、或者增加依赖库、工具等                   |
| revert   | 更新 | 回滚到上一个版本                                       |
| build    | 构建 | 系统构建或依赖项的更改，如升级依赖版本、修改构建脚本   |




## 删除本地文件

先输入命令查看

```
ls -l
```

在删除

```
rm -rf 前一个命令列出的文件名
```

