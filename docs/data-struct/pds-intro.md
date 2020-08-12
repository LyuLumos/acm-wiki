---
title: 简介 - 可持久化数据结构
---

## 简介

可持久化数据结构（Persistent data structure）每次修改都会保留其自身每一个历史版本

## 分类

### 部分可持久化

每个历史版本都可以访问，但只有最新的版本才可以修改

### 完全可持久化

每个历史版本都可以访问和修改

### 融合可持久化

每个历史版本都可以访问和修改，且支持通过合并两个历史版本来创建新版本

## 参考资料

- [Persistent data structure - Wikipedia](https://en.wikipedia.org/wiki/Persistent_data_structure)