---
title: golang多线程
date: 2017-11-28T00:00:00+08:00
categories: [技术]
tags: [golang]
---

最近在试着用``golang``做点东西,总结下golang的多线程

<!--more-->

> 什么是多线程

一个多线程程序包含两个或多个能并发运行的部分。 程序的每一部分都称作一个线程，并且每个线程定义了一个独立的执行路径。 多线程是多任务的一种特别的形式，但多线程使用了更小的资源开销。 这里定义和线程相关的另一个术语- 进程：一个进程包括由操作系统分配的内存空间，包含一个或多个线程。
