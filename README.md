# CS学习指南

这是一个计算机科学学习资源汇总项目，旨在为计算机科学和编程学习者提供全面的学习路线和优质资源推荐。

## 项目概述

本项目收集并整理了计算机科学不同领域的优质学习资源，包括但不限于：
- 编程语言入门（Python、C等）
- 计算机系统基础
- 数据库系统
- 实用工具和技能
- 推荐书籍

网站使用MkDocs构建，支持中英文双语环境。

## 本地运行说明

### 环境要求
- Python 3.6+
- pip (Python包管理器)

### 安装步骤

1. **克隆仓库**
   ```bash
   git clone https://github.com/ZH1995/CSStudyGuide.git
   cd CSStudyGuide
   ```

2. **创建并激活虚拟环境**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # 在Windows上使用: .venv\Scripts\activate
   ```

3. **安装依赖**
   ```bash
   pip install -r requirements.txt
   pip install mkdocs-material
   ```

4. **本地预览网站**
   ```bash
   mkdocs serve
   ```
   然后在浏览器中访问 http://127.0.0.1:8000

5. **关闭预览服务器与虚拟环境**
   - 按 `Ctrl+C` 停止预览服务器
   - 输入 `deactivate` 退出虚拟环境

### 构建静态网站

如需构建静态网站文件：
```bash
mkdocs build
```
构建结果将保存在 `site` 目录中。

## 项目结构

```
CSStudyGuide/
├── .github/workflows/   # GitHub Actions工作流配置
├── .venv/               # Python虚拟环境（本地开发用）
├── docs/                # 文档主目录
│   ├── en/              # 英文文档
│   ├── 必学工具/        # 工具类教程
│   ├── 编程入门/        # 编程语言教程
│   │   ├── Python/      # Python语言资源
│   │   └── C/           # C语言资源
│   ├── 计算机系统基础/  # 系统相关课程
│   ├── 数据库系统/      # 数据库相关课程
│   ├── 随笔记录/        # 博客文章
│   ├── index.md         # 网站首页
│   └── 好书推荐.md      # 推荐书籍列表
├── mkdocs.yml           # MkDocs配置文件
├── requirements.txt     # Python依赖列表
└── README.md            # 项目说明文件
```

## 内容贡献

欢迎通过以下方式贡献内容：

1. Fork本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个Pull Request

## 多语言支持

本项目使用`mkdocs-static-i18n`插件支持多语言。目前支持：
- 中文（默认）
- 英文

如需切换语言，可在网站界面上选择。

## 问题反馈

如果您发现任何问题或有改进建议，请[创建issue](https://github.com/ZH1995/CSStudyGuide/issues)或直接联系项目维护者。

## 许可证

本项目采用MIT许可证 - 详细信息请查看LICENSE文件

## 致谢

感谢所有课程创作者和开源项目贡献者，他们的杰出工作使本指南成为可能。

---

Copyright © 2017-2025 ZH1995

ZH1995: 以markdown的格式给我

GitHub Copilot: # CS学习指南

这是一个计算机科学学习资源汇总项目，旨在为计算机科学和编程学习者提供全面的学习路线和优质资源推荐。

## 项目概述

本项目收集并整理了计算机科学不同领域的优质学习资源，包括但不限于：

- 编程语言入门（Python、C等）
- 计算机系统基础
- 数据库系统
- 实用工具和技能
- 推荐书籍

网站使用MkDocs构建，支持中英文双语环境。

## 本地运行说明

### 环境要求
- Python 3.6+
- pip (Python包管理器)

### 安装步骤

1. **克隆仓库**
   ```bash
   git clone https://github.com/ZH1995/CSStudyGuide.git
   cd CSStudyGuide
   ```

2. **创建并激活虚拟环境**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # 在Windows上使用: .venv\Scripts\activate
   ```

3. **安装依赖**
   ```bash
   pip install -r requirements.txt
   pip install mkdocs-material
   ```

4. **本地预览网站**
   ```bash
   mkdocs serve
   ```
   然后在浏览器中访问 http://127.0.0.1:8000

5. **关闭预览服务器与虚拟环境**
   - 按 `Ctrl+C` 停止预览服务器
   - 输入 `deactivate` 退出虚拟环境

### 构建静态网站

如需构建静态网站文件：
```bash
mkdocs build
```
构建结果将保存在 `site` 目录中。

## 项目结构

```
CSStudyGuide/
├── .github/workflows/   # GitHub Actions工作流配置
├── .venv/               # Python虚拟环境（本地开发用）
├── docs/                # 文档主目录
│   ├── en/              # 英文文档
│   ├── 必学工具/        # 工具类教程
│   ├── 编程入门/        # 编程语言教程
│   │   ├── Python/      # Python语言资源
│   │   └── C/           # C语言资源
│   ├── 计算机系统基础/  # 系统相关课程
│   ├── 数据库系统/      # 数据库相关课程
│   ├── 随笔记录/        # 博客文章
│   ├── index.md         # 网站首页
│   └── 好书推荐.md      # 推荐书籍列表
├── mkdocs.yml           # MkDocs配置文件
├── requirements.txt     # Python依赖列表
└── README.md            # 项目说明文件
```

## 内容贡献

欢迎通过以下方式贡献内容：

1. Fork本仓库
2. 创建您的特性分支 (`git checkout -b feature/AmazingFeature`)
3. 提交您的更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 开启一个Pull Request

## 多语言支持

本项目使用`mkdocs-static-i18n`插件支持多语言。目前支持：
- 中文（默认）
- 英文

如需切换语言，可在网站界面上选择。

## 问题反馈

如果您发现任何问题或有改进建议，请[创建issue](https://github.com/ZH1995/CSStudyGuide/issues)或直接联系项目维护者。

## 许可证

本项目采用MIT许可证 - 详细信息请查看LICENSE文件

## 致谢

感谢所有课程创作者和开源项目贡献者，他们的杰出工作使本指南成为可能。