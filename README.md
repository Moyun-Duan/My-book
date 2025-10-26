# 我的大学手册 📚

[![LaTeX](https://img.shields.io/badge/Made%20with-LaTeX-1f425f.svg)](https://www.latex-project.org/)
[![License](https://img.shields.io/github/license/Moyun-Duan/My-book)](LICENSE)

## 📖 简介

这是我的个人大学手册，用于记录我的生活点滴和学业内容，包括错题、笔记、练习等。

**作者：** Moyun Duan（墨昀）

## 📑 内容结构

本手册分为以下几个主要部分：

### 第一章：引言
- 关于我
- 关于本手册

### 第二章：生活
- 生活点滴
- 志愿者活动
- 奇闻轶事

### 第三章：学业
- **微积分**
  - 重要笔记
  - 经典题目
- **线性代数**
  - 重要笔记
  - 经典题目
- **C语言程序设计**
  - 重要笔记
  - 经典题目
- **大学英语**
  - 作文
    - 内容积累
    - 反思改进

### 第四章：课余学习
- 香橙派
- Markdown学习
  - 求是潮的晚安短信
  - 求是潮内训
  - e志者协会课

## 🛠️ 编译说明

本手册使用 LaTeX 编写，使用 `XeLaTeX` 引擎编译。

### 环境要求
- TeX Live 2025 或更高版本
- XeLaTeX 编译器
- 中文字体支持（KaiTi、FangSong、Microsoft YaHei）

### 编译命令

```bash
# 编译两次以生成完整的目录
xelatex main.tex
xelatex main.tex
```

### VS Code 用户

如果您使用 VS Code + LaTeX Workshop 扩展，项目已配置为自动使用 XeLaTeX 编译。直接保存文件即可自动编译。

## 📦 项目文件

- `main.tex` - 主 LaTeX 文档
- `mystyle.sty` - 自定义样式包
- `.vscode/settings.json` - VS Code 配置
- `main.pdf` - 编译生成的 PDF 文件

## 📝 使用的宏包

- `amsmath` - 数学公式支持
- `ctex` - 中文支持
- `graphicx` - 图片插入
- `listings` - 代码高亮
- `xcolor` - 颜色支持
- `fancyvrb` - 增强的文本显示
- `fontspec` - 字体管理
- `geometry` - 页面布局
- `titlesec` - 标题格式
- `fancyhdr` - 页眉页脚

## 📄 许可证

本项目采用 MIT 许可证 - 详见 [LICENSE](LICENSE) 文件

## 🔗 联系方式

如有问题或建议，欢迎通过 GitHub Issues 联系我。

---

*最后更新：2025年10月26日*
