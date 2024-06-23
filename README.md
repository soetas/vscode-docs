# vscode-docs

## 用户和工作区

```powershell
code .

```

> 代码重构

## 配置

打开命令面板快捷键: `shift + ctrl + p`

## 默认设置

### 用户设置

> 多行编辑和自定义快捷键

常用快捷键:

1. 复制光标所在行： `ctrl + c`
2. 替换文本: `ctrl + h`
3. 光标所在行的上方插入一行: `shift + ctrl + enter`
4. 光标所在行的下方插入一行: `ctrl + enter`
5. 文件夹内查找: `shift + ctrl + f`
6. 文档格式化: `shift + alt + f`
7. 切换终端面板: `` ctrl + ` ``
8. 关闭当前文件: `ctrl + w`

[Keyboard shortcuts for Windows](https://code.visualstudio.com/shortcuts/keyboard-shortcuts-windows.pdf)

settings.json:

```json
{
  "editor.formatOnSave":true,
  "editor.minimap.enabled":true,
  "editor.linkedEditing": true,
  "files.insertFinalNewline": true 

{

```

### 工作区设置

## 调试

配置文件(launch.json):

```json5
{
  "configurations": [
    {
      "name": "Launch Program",
      "program": "${workspaceFolder}/app.js",
      "request": "launch",
      "skipFiles": [
        "<node_internals>/**"
      ],
      "type": "node"
    }
  ]
}

```

## 扩展插件

> 智能感知、代码片段和Emmet语法

```json
{
  "Print to console": {
    "prefix": "log",
    "body": [
      "console.log('$1')",
      "$2"
		],
    "description": "Log output to console"
  }
}


```

[CSS Peek](https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek)

[Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)

[Icon Fonts](https://marketplace.visualstudio.com/items?itemName=idleberg.icon-fonts)

[Auto Rename Tag](https://marketplace.visualstudio.com/items?itemName=formulahendry.auto-rename-tag)

[Color Info](https://marketplace.visualstudio.com/items?itemName=bierner.color-info)

[LiveServer](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)

[Carbon Now Sh](https://marketplace.visualstudio.com/items?itemName=ericadamski.carbon-now-sh)

[EditorConfig](https://marketplace.visualstudio.com/items?itemName=EditorConfig.EditorConfig)

[Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager)

[Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)

[Path Intellisense](https://marketplace.visualstudio.com/items?itemName=christian-kohler.path-intellisense)

[Turbo Console Log](https://marketplace.visualstudio.com/items?itemName=ChakrounAnas.turbo-console-log)

