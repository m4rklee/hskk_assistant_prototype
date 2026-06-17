# HSKK Assistant Prototype

> An Axure prototype for a Chinese speaking test assistant.

汉考口语助手原型图是一个面向 HSKK/汉语口语练习场景的产品设计原型。仓库主要保存 Axure 原型压缩包，用于展示口语练习、题目流程、用户交互和产品信息架构。

## Highlights

- **Speaking practice scenario**: 聚焦汉语口语考试练习和学习辅助。
- **Prototype-first design**: 使用 Axure 表达页面结构、交互流程和产品体验。
- **Portfolio-friendly artifact**: 适合用于课程展示、产品设计说明和早期需求沟通。

## Demo / Preview

仓库包含：

```text
hskk.zip
```

使用方式：

1. 下载或克隆本仓库。
2. 解压 `hskk.zip`。
3. 使用浏览器打开解压后的入口 HTML 文件。

## How It Works

```text
Learner
   |
   v
Prototype pages
   |
   +--> speaking practice flow
   +--> task guidance
   +--> result / feedback screens
   +--> product navigation
```

该仓库目前是交互原型，不包含后端服务、数据库或真实 AI 模型调用。

## Features

| Module | Description |
|---|---|
| **Product Flow** | 展示口语助手从进入、练习到结果反馈的核心路径。 |
| **Interaction Prototype** | 使用 Axure 静态交互表达页面跳转和操作逻辑。 |
| **Design Reference** | 可作为后续 Web 或 App 开发的需求参考。 |

## Tech Stack

- **Design Tool**: Axure
- **Artifact**: Static HTML prototype package
- **Runtime**: Browser preview after unzip

## Quick Start

```bash
git clone https://github.com/m4rklee/hskk_assistant_prototype.git
cd hskk_assistant_prototype
unzip hskk.zip -d hskk
```

然后在浏览器中打开解压目录中的 HTML 入口文件。

## Project Structure

```text
.
├── README.md
└── hskk.zip             # Axure generated prototype package
```

## Notes

- 本仓库只包含产品原型，不包含可运行的 AI 服务。
- 如需工程化实现，可基于该原型继续拆分前端页面、口语评测服务和数据模型。

## Roadmap

- Add exported screenshots for GitHub preview.
- Add product requirement notes.
- Split prototype pages into a web implementation plan.
