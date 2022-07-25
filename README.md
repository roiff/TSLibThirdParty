# 使用

1. 项目依赖 [Lua](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) 插件，请先安装该插件。
2. 克隆项目

```
git clone https://github.com/roiff/luaThirdParty.git
```
3. 在 Lua 插件中设置中打开 `Check Third Party` 选项
![avatar](https://raw.githubusercontent.com/roiff/TSLibThirdParty/master/img/CheckThirdParty.png)

4. 在 Lua 插件中设置中配置外部库，打开设置中 `Lua.workspace.userThirdParty` 设置项，User Third Party
![avatar](https://raw.githubusercontent.com/roiff/TSLibThirdParty/master/img/UserTirdParty.png)

5. 将设置项替换为该项目的绝对路径，保存

6. 找到 `Workspace: Preload File Size` 选项，确保所设置的数值大于项目中`TouchSprite.lua`的文件大小，否者设置完成后不会加载,他的大小大约为150kb，设置大于这个数值
![avatar](https://raw.githubusercontent.com/roiff/TSLibThirdParty/master/img/PreloadFileSize.png)
