# KG-Reasoning from scratch
从零开始构建基于知识图谱的推理

项目基于[PoG](https://deepwiki.com/liyichen-cly/PoG/)

# 环境准备

首先需要部署Freebase知识图谱到本地机器。这是系统运行的基础，因为所有的知识图谱查询都依赖于本地的SPARQL端点。

## Freebase

Freebase 是一个由 Google 支持的开源知识图谱项目，它的核心目的是将世界上的结构化信息组织成一个可供机器理解和查询的知识库。Freebase包含实体（Entities）、类（Types）和属性（Properties），并通过关系（Relations）将实体连接起来。它的目标是把“事实”和“概念”以结构化形式存储，方便程序进行语义搜索、问答、推荐等应用。