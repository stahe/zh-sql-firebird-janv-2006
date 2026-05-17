# 基于 Firebird 数据库管理系统（DBMS）的 SQL 入门指南

➡️ 相关课程：**[基于 Firebird 数据库管理系统（DBMS）的 SQL 入门指南](https://stahe.github.io/zh-sql-firebird-janv-2006/)**

## 概述

本文档是对应用于 **Firebird 数据库管理系统** 的 **SQL（结构化查询语言）** 的入门介绍。
本文档改编自一份于 **1991 年为 Oracle 编写** 的旧教学文档，而该文档又主要参考了 Oracle 的官方文档以及以下书籍：

* *SQL – 入门、编程与精通*
  作者为 **Christian Marée** 和 **Guy Ledant**，由 Eyrolles 出版。 

SQL 是一种 **用于创建、管理及对关系型数据库执行查询的标准语言**。
它在很大程度上与所使用的数据库管理系统（DBMS）无关，尽管某些DBMS会引入专有扩展。 

## 为什么选择Firebird？

本文中的示例使用的是**Firebird DBMS**。
做出这一选择的原因在于它具有一项在教学环境中特别实用的特性：一个Firebird数据库可以**包含在一个单一文件中**。

这使得我们可以：

* 轻松将数据库复制到 **U盘** 上;
* 在 **不同计算机** 上使用（如家中、大学、实验室）；
* 无需复杂的基础设施即可进行操作;

## SQL 兼容性

尽管示例是针对 Firebird 编写的，但其中大部分内容也可在其他关系型数据库管理系统（DBMS）中复现，例如：
* MySQL
* PostgreSQL
* Firebird
* SQL Server Express
* Microsoft Access
* Oracle
所有这些系统均使用 SQL，有时会包含**特定产品的变体或扩展**。

## 目标读者

本文档面向：

* **希望学习 SQL 的初学者**
* 希望**复习该语言基础知识**的人士

本文重点在于学习**基础 SQL**。

## 范围排除项

某些主题已被有意省略：

* 存储过程
* 高级 SQL 编程
* SQL API
* DBMS 管理

本指南旨在提供**清晰且循序渐进的 SQL 语言入门**。

Serge Tahé，2006年1月