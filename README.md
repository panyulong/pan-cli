
### 安装依赖

```
npm install 
```

### 项目创建

当前目录下执行下面命令（本地调试的时候如果需要 pan-cli 命令在全局生效，执行 npm link 即可）

```
pan-cli create projectname
```

### 更新版本号
比如我想来个1.0.1版本，注意，是最后一位修改了增1，那么命令：
```
npm version patch    回车就可以了；
```
比如我想来个1.1.0版本，注意，是第二位修改了增1，那么命令：
```
npm version minor    回车就可以了；
```
比如我想来个2.0.0版本，注意，是第一位修改了增1，那么命令：
```
npm version major     回车就可以了；
```

2、修改远端的版本,提交到远端npm中：
```
npm publish 
```

