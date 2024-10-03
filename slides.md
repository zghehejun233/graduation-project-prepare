---
theme: seriph
background: https://cover.sli.dev
title: 毕业设计开题
titleTemplate: '%s - ThuRAY'
drawings:
  persist: false
transition: slide-left
mdc: true
overviewSnapshots: true
---

# 毕业设计

<!-- ---

```yaml
hideInToc: true
```

# 目录

<Toc maxDepth=2 /> -->

<!-- 目录页 -->

---

```yaml
layout: image-right
image: https://cover.sli.dev
```

# 选题背景

## 选择有意义、有价值的课题

---

```yaml
layout: two-cols-header
```

# 选题背景

::left::

## 实用

项目能够在实际中应用并产生价值

::right::

## 创新

解决现有的问题，提出新的方法

---

```yaml
layout: quote
```

# "Best Practice"

## 提炼最佳实践

总结本科学习和实习经验，归纳项目所涉及语言、框架、工具的最佳实践

---

```yaml
layout: image-right
image: https://cover.sli.dev
```

# 备选题目

## 一些积累下来的想法

- Flutter神经网络部署插件
- 存算分离的云原生分布式搜广推中间件
- 无人机消息数据采集与分析系统
- 知识图谱与RAG驱动的文旅LLM应用
- 基于Go与Next.js的脚手架工具

---

# Flutter神经网络部署插件

通过Flutter插件实现神经网络模型的部署，提供简单易用的API。

## 痛点分析

- Flutter开发者无法直接部署神经网络模型
- 神经网络模型部署需要专业知识
- ONNX Runtime、MNN、TFLite等方案依靠C++插件
- IPC通信、性能损耗、部署复杂度高

Flutter对于跨平台开发十分友好，开源社区并没有为客户端神经网络部署提供通用的解决方案。</br>

同时，随着LLM时代的到来，端侧推理能力越来越重要，一种更加便捷、通用的解决方案迫在眉睫。

---

# Flutter神经网络部署插件

通过Flutter插件实现神经网络模型的部署，提供简单易用的API。

## 解决方案

考虑到Flutter的跨平台特性，我们可以通过Dart的FFI功能调用C++代码，实现对ONNX Runtime、MNN、TFLite等神经网络推理库的封装。

具体实现中，可以从以下几个方面考虑：

- 推理框架的选择
- 神经网络模型的加载
- 推理结果的处理
- API的设计

---

# Flutter神经网络部署插件

通过Flutter插件实现神经网络模型的部署，提供简单易用的API。

## 解决方案

在解决基本问题的基础上，我们还可以考虑以下几个方面：

- 模型的预加载与热更新
- 多种推理框架的支持以及切换
- 基于Sentry对模型推理的监控与报警
- 测试自动化与持续集成

---

# Flutter神经网络部署插件

## 预期成果

一个支持多种神经网络推理框架的Flutter插件，提供简单易用的API，支持模型的预加载与热更新，监控与报警，测试自动化与持续集成。

---

# 存算分离的云原生分布式搜广推中间件

---

# 无人机消息数据采集与分析系统

---

# 知识图谱与RAG驱动的文旅LLM应用

---

# 基于Go与Next.js的脚手架工具

---

```yaml
layout: image-right
image: https://cover.sli.dev
```

# 项目计划

## 毕业设计的时间安排
