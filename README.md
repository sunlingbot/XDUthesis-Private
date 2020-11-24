# XDUthesis-private

这里是西安电子科技大学实验报告 `LaTeX` 模板，由于电院的老师没有对实验报告的模板格式做任何要求，于是就对 `XDUthesis` 模板做了些许修改。**如果老师有明确要求，请勿使用此模板。**

图片logo来自这里：[https://xcb.xidian.edu.cn/info/1008/1094.htm](https://xcb.xidian.edu.cn/info/1008/1094.htm)

## 模板说明
- 本模板谨按照电院的要求作出了最小适配，同时较为私人化，**如果老师有明确要求，请勿使用此模板。**
- 请按照目录树使用**相对路径**的方式引用各类示例文件。
- 请将引用图片移入 `figure` 目录，请使用 `.jpg` 或 `.png` 常见格式，如果使用 `.eps` 格式则不可预览，算是一个小小的 BUG 吧！
- 请将引用源代码移入 `code` 目录。
- 代码字体为 `IBM Plex Mono`，没有的话换一个或下载安装，然后在类中声明即可。
- 如果对现有样式不满意，请自行修改 `xdureport.cls` 类文件。

## 文档目录与编译方式

本模板在 `Windows` 环境完美运行，使用引擎 `TexLive 2020` 、编辑器 `TeXstudio` ，编译方式为 `xelatex` 配 `bibtex`，编码方式为 `UTF-8`。
 
```bash
XDUthesis-private
├─ chapter                                  # 各个章节
│    ├─ article.tex                         # 实验报告正文部分                  
├─ figure                                   # 示例图片
│    ├─ xdubanner.jpg                       # 西电头图
│    └─ xdulogo.jpg                         # 西电校徽 logo
├─ code                                     # 代码文件
│    └─ demo.c                              # 一个C语言样例代码
├─ books.bib                                # 参考文献的 bib 文件
├─ main.bbl                                 # 编译生成的 bbl 文件，不用管
├─ main.pdf                                 # 结果 pdf 文件
├─ main.tex                                 # 要编译的主文件
└─ xdureport.cls                            # 要导入的文档类
```

## 相关项目
- [xduthesis](https://github.com/fredqi/xduthesis)
- [XDU-report-LaTeX-template](https://github.com/muyuuuu/XDU-report-LaTeX-template)