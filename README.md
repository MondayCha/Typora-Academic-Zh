# Typora 中文学术风格主题

## 关于主题

基于Typora官方的Academic以及[zh-academic](https://github.com/ZJUGuoShuai/zh-academic)主题，正文字体采用华文中宋，等宽字体采用CamingoCode。

和Academic的区别主要在代码块上，我更偏爱带有外边框的代码样式，示例可参看`README.pdf`。

```python
# This is a useless sample code
import taichi as ti
ti.init(debug=False, arch=ti.cuda)
```

## 安装方式

直接下载本仓库为 ZIP，将内容（`academic-zh/` 和 `academic-zh.css`）解压缩至 Typora 主题文件夹内（Typora主题文件夹打开方式：菜单→主题→打开主题文件夹）。

## 其他说明：

- 可使用`<div style='text-align:right'></div>`的方式右对齐
- 可使用`<center></center>`的方式居中对齐
- 可使用`<div style="page-break-after:always;"></div>`在输出PDF时分页

