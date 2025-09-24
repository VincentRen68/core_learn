# Coze Studio 项目总结

## 1. 项目概述

Coze Studio 是一个一站式的 AI Agent 可视化开发平台，旨在简化 AI 应用的创建、调试和部署过程。它源于服务数百万开发者的“扣子开发平台”，并将其核心引擎开源。开发者可以通过零代码或低代码的方式，利用平台提供的丰富工具和框架，快速构建强大的 AI Agent 和工作流。

## 2. 核心功能

- **AI Agent 开发核心技术**: 集成了 Prompt、RAG（检索增强生成）、插件（Plugin）和工作流（Workflow）等关键技术。
- **模型服务管理**: 支持接入并管理多种在线或离线的大语言模型，如 OpenAI、火山方舟等。
- **可视化编排**: 提供可视化的画布，通过拖拽节点即可快速搭建和调试智能体、应用和工作流。
- **资源管理**: 支持创建和管理插件、知识库、数据库和提示词等开发资源。
- **API 与 SDK**: 提供 OpenAPI 和 Chat SDK，方便将构建的 AI Agent 集成到现有业务系统中。

## 3. 技术架构

- **后端**: 采用 Go 语言开发，基于微服务架构，并遵循领域驱动设计（DDD）原则，保证了系统的高性能、高扩展性和可维护性。
- **前端**: 使用 React 和 TypeScript 构建，提供了现代化的用户交互体验。
- **部署**: 项目使用 Docker 和 Docker Compose 进行容器化部署，简化了环境配置和启动流程。

## 4. 快速上手

1.  **环境要求**: 至少 2 核 CPU、4 GB 内存，并安装 Docker 和 Docker Compose。
2.  **获取源码**: `git clone https://github.com/coze-dev/coze-studio.git`
3.  **配置模型**: 在 `backend/conf/model/` 目录下配置至少一个可用的模型服务（如火山方舟）。
4.  **启动服务**: 在 `docker` 目录下执行 `docker compose up -d` 即可启动所有服务。
5.  **访问**: 通过浏览器访问 `http://localhost:8888` 即可打开 Coze Studio。

## 5. 社区与贡献

Coze Studio 拥有一个开放和友好的开发者社区，欢迎开发者通过 GitHub Issues、Pull Requests 等方式参与贡献。同时，项目提供了飞书、Discord 和 Telegram 等多种技术交流渠道。

