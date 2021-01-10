# 编译scss到css
## npm模块编译
```
npm install sass -g

sass --watch 路径 编译后的路径
```
## vscode的插件

> 安装扩展:live sass compiler

设置 -> settings -> format:

```
    "liveSassCompile.settings.formats": [

        {
            "format": "compressed",     //压缩格式,  expanded非压缩格式
            "extensionName": ".css",
            "savePath": "/css"          //编译后的路径
        }
    ],
```

点击vscode 命令行下边的watch sass,自动编译成css

# scss中的变量
```
$color-blue:#0000ff
//以$开头
```