# Keleeke — AI Stem Splitter (Keleeke.com)

Last updated: 2026-01-28

## Overview
Keleeke is an online AI stem splitter for creators and music lovers. It makes audio separation simple and browser-based: upload audio, split vocals and instruments, and download results for further creation.

> **Links**
> - Website: https://keleeke.com/
> - Pricing: https://keleeke.com/pricing
> - Core tool (stem splitter): https://keleeke.com/tools/stem-splitter
> - Vocal removal: https://keleeke.com/tools/remove-vocals
> - Acapella extractor: https://keleeke.com/tools/acapella-extractor

## One‑Line Pitch
An online AI vocal/instrument separation tool—upload audio, split tracks, and download results.

## What It Does
- Web-based stem separation (no installation required)
- Model selection and multi-model comparison (up to 3 models)
- Job dashboard for uploads, progress, history, and errors
- Single-file and ZIP batch downloads
- Multi-language UI with consistent design system

## Typical Use Cases
- Vocal/accompaniment separation before mixing
- Content cleanup for podcasts and video voiceovers
- Sampling and remix preparation
- A/B testing between separation models

## Simple Workflow
1) Open the tool
2) Upload audio/video
3) Choose model(s)
4) Submit and track progress
5) Download separated stems

## Tech & Infrastructure (brief)
- Next.js 16 + React 19 + TypeScript + Tailwind CSS v4
- BullMQ + Redis workers for processing
- Tencent COS (S3‑compatible) storage
- Models: BS‑Roformer, Melband‑Roformer

---

# Keleeke — AI Stem Splitter（Keleeke.com）

更新日期：2026-01-28

## 概述
Keleeke 是面向创作者与音乐爱好者的在线 AI Stem Splitter。无需安装，浏览器内上传音频即可分离人声与乐器，并下载结果继续创作。

> **相关链接**
> - 官网：https://keleeke.com/
> - 定价：https://keleeke.com/pricing
> - 核心工具（Stem Splitter）：https://keleeke.com/tools/stem-splitter
> - 人声移除：https://keleeke.com/tools/remove-vocals
> - Acapella 提取：https://keleeke.com/tools/acapella-extractor

## 一句话介绍
在线 AI 人声/乐器分离工具：上传音频即可分离并下载结果。

## 能力概览
- 在线分离（无需安装）
- 模型选择与多模型对比（最多 3 模型）
- 任务控制台：上传、进度、历史与错误提示
- 单文件与 ZIP 批量下载
- 多语言界面与统一 UI 规范

## 典型场景
- 混音前的人声/伴奏分离
- 播客与视频口播清理
- 采样与 Remix 准备
- 模型效果对比与试听测试

## 简化流程
1) 进入工具
2) 上传音频/视频
3) 选择模型（可多模型对比）
4) 提交任务并查看进度
5) 下载分离结果

## 技术与基础设施（简版）
- Next.js 16 + React 19 + TypeScript + Tailwind CSS v4
- BullMQ + Redis Worker 任务处理
- Tencent COS（S3 兼容）对象存储
- 模型：BS‑Roformer、Melband‑Roformer
