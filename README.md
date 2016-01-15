## SublimeText配置文件

#### 具体步骤
- 官网下载SublimeText 3 Build最新版本（或者3095版本）。
- 安装启动，输入序列号。
- 打开终端并输入：
```
cd Library/Application\ Support/Sublime\ Text\ 3/Packages/User
git clone git@github.com:bitmonk404/subl_config.git
mv subl_config/* .
rm -rf subl_config
```
- 在SublimeText中使用ctrl + `打开终端面板，安装Package Control。  
Package Control安装过程中根据User目录中的配置文件，将自动安装所有插件以及你自己的所有个性化设置。

#### 配置文件注释
```javascript
{
    // 显示minimap的当前位置
    "always_show_minimap_viewport": true,
    // 文件夹字符加粗
    "bold_folder_labels": true,
    // 颜色样式
    "color_scheme": "Packages/Material Theme/schemes/Material-Theme-OceanicNext.tmTheme",
    // 默认编码
    "default_encoding": "UTF-8",
    // 是否允许拖拽字符
    "drag_text": false,
    // minimap是否加上边框
    "draw_minimap_border": true,
    // 无论鼠标是否在行号边缘，代码折叠一直显示。
    "fade_fold_buttons": false,
    // sidebar中不显示的文件
    "file_exclude_patterns":
    [
        ".DS_Store"
    ],
    // sidebar中不显示的文件夹
    "folder_exclude_patterns":
    [
        "__pycache__",
        ".git"
    ],
    // 字体类型
    // Menlo是xcode默认字体。
    // Menlo比Monaco要扁一些，意味着显示同样多的行数它看起来字体会大一些（因为可以把字号调大些）。
    "font_face": "Menlo",
    // 字号大小
    "font_size": 14,
    // 高亮当前行
    "highlight_line": true,
    // 高亮修改过的文件的tab标签
    "highlight_modified_tabs": true,
    // 忽略的插件
    "ignored_packages":
    [
        "Markdown",
        "Vintage"
    ],
    // 缩进显示样式设置
    // draw_normal表示会有一条虚线显示该缩进。
    // draw_active表示光标停留在某行的时候会高亮该缩进的虚线
    "indent_guide_options":
    [
        "draw_normal",
        "draw_active"
    ],
    // 行距
    "line_padding_bottom": 3,
    // 行距
    "line_padding_top": 3,
    // 只有上下拉动页面的时候，才显示滚动条
    "overlay_scroll_bars": "enabled",
    // 让文件最后一行离底部有一段距离的高度
    // 这个特性非常重要，不然每次代码写到最后一行的时候都超级累。
    "scroll_past_end": true,
    // 在页面右下显示编码格式
    "show_encoding": true,
    // 样式
    "theme": "Material-Theme.sublime-theme",
    // 将tab转换为空格
    "translate_tabs_to_spaces": true,
    // 一个tab等于4个空格
    "tab_size": 4,
    // 自动换行
    "word_wrap": true
}
```