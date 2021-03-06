---
layout: post
title: 'Sublime 插件列表'
date: '2017-02-02'
header-img: "img/post-bg-unix.jpg"
tags:
     - Editor
     - Sublime
author: 'Bro Qiang'
---

## 插件列表

#### `Material Theme`

主题, 个人比较喜欢的一个主题+配色

#### `A File Icon`

文件图标, 可以叫左侧菜单出现对应文件类型的图标

#### `DocBlockr`

自动注释成功工具

**配置**

```json
{
    "jsdocs_extra_tags":["@Author: BroQiang <broqiang@qq.com>","@DateTime {{datetime}}"], // 自定义的内容
    "jsdocs_align_tags": "shallow", // 取消自动对齐, 个人不喜欢,间距太大了
}
```

####  `AdvancedNewFile`

非常方便的快速创建文件插件，快捷键 `Super+Alt+n`

#### `PHP Companion`

直译过来是叫 PHP 伴侣, 可以自动引入PHP命名空间等

**配置快捷键**

```json
[
    { "keys": ["f9"], "command": "expand_fqcn" }, //自动补全命名空间
    { "keys": ["f8"], "command": "find_use" }, //自动寻找命名空间
    { "keys": ["f7"], "command": "insert_php_constructor_property" }, //自动生产构造函数
]
```

#### `CodeFormatter`

代码格式化工具,可以很好的格式化 PHP 代码,也支持JS Css等,不过效果不好，快捷键 `Ctrl+Alt+F`

#### `HTML-CSS-JS Prettify`

可以很好的格式化Html js css,需要Node.js支持， 快捷键 `Ctrl+Shift+H`

#### `InputHelper`

Sublime for Linux 输入中文的解决方案, 详细的配置见

#### Emment

高效编写HTML的工具，原zen-coding

#### `Terminal`

调用终端,使用起来很方便,可以直接显示当前文件目录,这个比较方便,避免切换目录浪费时间， 快捷键 `Ctrl+Shift+t`

#### `SideBarEnhancements`

左侧菜单增强工具，功能很强大，不过个人不喜欢，一下多了很多,感觉有点乱，所以就没有安装

#### `SyncedSideBar`

自动在左边文件夹树中定位当前文件

#### `EditorConfig`

`.editorconfig` 编码格式化支持

#### `ColorPicker`

直接在sublime里调用调色板的工具，也算是比较实用的一个工具，快键键 `Ctrl+Shift+C`

#### `AutoFileName`

自动完成路径的文件，不过在 PHP 中不是很好用。

#### `GitGutter`

在侧边栏高亮你的文件内容变动，增加，删除，修改，类似git diff一样的效果

#### Markdown 插件

- `MarkdownEditing` - Markdown编写非常好用的一个插件

- `Markdown Preview` - Markdown 预览插件,可以支持 Github 风格

- `Table Editor` - Markdown 表格自动生成

#### 语法检测工具

- `SublimeLinter` - 语法检测工具

- `SublimeLinter-php` - PHP 语法检测，依赖于 SublimeLinter

#### `StatusBarTime`

可以在状态栏显示时间, 挺有用的, 尤其是Sublime全屏开发的时候

#### Laravel 支持

- `Laravel 5 Snippets` - Laravel 语法支持

- `Laravel Blade Highlighter` - Laravel Blade 模板语法高亮

- `Blade Snippets` - Laravel Blade Snippets 模板标签自动完成