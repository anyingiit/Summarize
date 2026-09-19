[English](README.md) · **简体中文**

> 英文版是规范版本。本页与 [README.md](README.md) 不一致时，以英文版为准。

<!-- translation-of: README.md sha256:f8cd921d2fcbcc39 -->

<!-- Source: Best-README-Template BLANK_README (Unlicense) — https://github.com/othneildrew/Best-README-Template -->
<a id="readme-top"></a>

# Summarize

Summarize 是一个公开仓库，目前只包含项目脚手架（例如议题模板、贡献指南和许可证），没有任何语言的应用源码、清单或入口点。

[![License](https://img.shields.io/github/license/anyingiit/Summarize)](LICENSE)

[报告问题](https://github.com/anyingiit/Summarize/issues/new?template=bug_report.yml) · [提出需求](https://github.com/anyingiit/Summarize/issues/new?template=feature_request.yml)

<details>
  <summary>目录</summary>
  <ol>
    <li><a href="#about-the-project">关于本项目</a></li>
    <li><a href="#getting-started">开始使用</a></li>
    <li><a href="#usage">用法</a></li>
    <li><a href="#contributing">参与贡献</a></li>
    <li><a href="#license">许可证</a></li>
    <li><a href="#contact">联系方式</a></li>
  </ol>
</details>

## 关于本项目

Summarize 目前只是一个公开的治理与 CI 脚手架仓库——包含 [`.github/ISSUE_TEMPLATE/bug_report.yml`](.github/ISSUE_TEMPLATE/bug_report.yml) 这样的议题模板、一份[拉取请求模板](.github/PULL_REQUEST_TEMPLATE.md)，以及 [`CONTRIBUTING.md`](CONTRIBUTING.md)——没有任何语言的应用源码、包清单或入口点。它是从一个文档与 CI 起始套件创建的，至今还没有提交过任何代码。

计划中的功能与已知问题，见[未解决的议题](https://github.com/anyingiit/Summarize/issues)。

## 开始使用

### 环境要求

- 需要 Python 3 和 `pre-commit` 包，仅用于运行 [`.pre-commit-config.yaml`](.pre-commit-config.yaml) 中声明的检查钩子（trailing-whitespace、end-of-file-fixer、check-yaml、check-merge-conflict、check-added-large-files）。除此之外不需要任何东西，因为这里没有应用程序可以构建。

### 安装

目前没有可供安装的包清单；克隆仓库即可查看其脚手架内容，启用检查钩子是可选的。

```sh
git clone https://github.com/anyingiit/Summarize.git
cd Summarize
pre-commit install
```

## 用法

这个仓库目前没有可运行的程序。在加入源码之前，唯一面向用户的入口是通过 [`.github/ISSUE_TEMPLATE/`](.github/ISSUE_TEMPLATE) 和 [`.github/PULL_REQUEST_TEMPLATE.md`](.github/PULL_REQUEST_TEMPLATE.md) 下的模板提交议题或拉取请求。

## 参与贡献

欢迎任何形式的贡献。阅读 [CONTRIBUTING.md](CONTRIBUTING.md) 了解如何提交议题或拉取请求，阅读 [CODE_OF_CONDUCT.md](CODE_OF_CONDUCT.md) 了解参与者应遵守的行为准则。

请不要在公开的议题或拉取请求中报告安全问题。[SECURITY.md](SECURITY.md) 说明了如何私下报告安全问题。

## 许可证

基于 MIT 许可证发布。详情见 [LICENSE](LICENSE)。

## 联系方式

项目链接：[https://github.com/anyingiit/Summarize](https://github.com/anyingiit/Summarize)

<p align="right">(<a href="#readme-top">回到顶部</a>)</p>
