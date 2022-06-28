# 使用

1. 项目依赖 [Lua](https://marketplace.visualstudio.com/items?itemName=sumneko.lua) 插件，请先安装该插件。
2. 克隆项目

```
git clone https://github.com/roiff/luaThirdParty.git
```
3. 在 Lua 插件中设置中配置外部库，打开设置中 `Lua.workspace.userThirdParty` 设置项，User Third Party

4. 将设置项替换为你这边存放文件的绝对路径，保存

5. 找到 `Workspace: Preload File Size` 选项，确保所设置的数值大于文件数值，否者设置完成后不会加载
