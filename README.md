# 依赖和下载

1. 项目依赖 [Lua](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) 插件，请先安装该插件。
2. 克隆项目

```
git clone https://github.com/roiff/luaThirdParty.git
```
# 使用方法一(自动检测匹配项目)

这个方法可以自动检测项目并配置，对于除了触动以外其他lua项目的人来说，会增加VSCode的运行速度

1. 在 Lua 插件中设置中打开 `Check Third Party` 选项
![avatar](https://raw.githubusercontent.com/roiff/TSLibThirdParty/master/img/CheckThirdParty.png)

2. 在 Lua 插件中设置中配置外部库，打开设置中 `Lua.workspace.userThirdParty` 设置项，User Third Party
![avatar](https://raw.githubusercontent.com/roiff/TSLibThirdParty/master/img/UserTirdParty.png)

3. 将设置项替换为该项目的绝对路径，保存

4. 找到 `Workspace: Preload File Size` 选项，确保所设置的数值大于项目中`TouchSprite.lua`的文件大小，否者设置完成后不会加载,他的大小大约为150kb，设置大于这个数值
![avatar](https://raw.githubusercontent.com/roiff/TSLibThirdParty/master/img/PreloadFileSize.png)

# 使用方法二(手动添加)
1. 在 Lua 插件中设置中配置外部库，打开设置中 `Lua.workspace.Library` 设置项
![avatar](https://raw.githubusercontent.com/roiff/TSLibThirdParty/master/img/LibrarySetting.png)

2. 将设置项替换为该项目的绝对路径下`TouchSprite/library`，子目录，如上图所示，保存

3. 找到 `Workspace: Preload File Size` 选项，确保所设置的数值大于项目中`TouchSprite.lua`的文件大小，否者设置完成后不会加载,他的大小大约为150kb，设置大于这个数值
![avatar](https://raw.githubusercontent.com/roiff/TSLibThirdParty/master/img/PreloadFileSize.png)
