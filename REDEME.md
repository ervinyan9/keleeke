# Keleeke — AI Stem Splitter (Keleeke.com)

Last updated: 2026-01-28

## Overview
Keleeke is an online AI stem splitter for creators and music lovers. It makes audio separation simple and browser-based: upload audio, split vocals and instruments, and download results for further creation.

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

## Pricing Snapshot
Billing is based on Processing Minutes (PM):
- PM = media duration (minutes) × number of models
- Free quota and paid balance can be stacked; free quota is consumed first

Free
- 15 PM per 24 hours
- Up to 7 jobs per day
- Single file ≤ 8 minutes, upload ≤ 100MB
- Basic model set (single-model only)

Paid (US)
- OneTime: $1 / job (60 PM, one-time only)
- Plus: $9 (300 PM, never expires)
- Pro: $19 (700 PM, never expires)

Paid (CN)
- OneTime: ¥6 / job (60 PM, one-time only)
- Plus: ¥59.9 (300 PM, never expires)
- Pro: ¥129 (700 PM, never expires)

## Key Limits & Notes
- Multi‑model comparison increases consumption by model count
- Free quota resets every 24 hours (no rollover)
- Results depend on source quality and model selection

## Tech & Infrastructure (brief)
- Next.js 16 + React 19 + TypeScript + Tailwind CSS v4
- BullMQ + Redis workers for processing
- Tencent COS (S3‑compatible) storage
- Models: BS‑Roformer, Melband‑Roformer

## Links
- Website: https://keleeke.com/
- Pricing: https://keleeke.com/pricing
- Core tool (stem splitter): https://keleeke.com/tools/stem-splitter
- Vocal removal: https://keleeke.com/tools/remove-vocals
- Acapella extractor: https://keleeke.com/tools/acapella-extractor

---

# Keleeke — AI Stem Splitter（Keleeke.com）

更新日期：2026-01-28

## 概述
Keleeke 是面向创作者与音乐爱好者的在线 AI Stem Splitter。无需安装，浏览器内上传音频即可分离人声与乐器，并下载结果继续创作。

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

## 计费摘要
按“处理分钟（PM）”计费：
- PM = 音视频时长（分钟）× 模型数量
- 免费额度与付费余额可叠加，优先消耗免费额度

Free（免费）
- 15 PM / 24 小时
- 单日任务上限 7 次
- 单文件 ≤ 8 分钟，上传 ≤ 100MB
- 基础模型集合，仅单模型

US 价表（USD）
- OneTime：$1 / 次（60 PM，仅本次任务有效）
- Plus：$9（300 PM，永久有效）
- Pro：$19（700 PM，永久有效）

CN 价表（CNY）
- OneTime：¥6 / 次（60 PM，仅本次任务有效）
- Plus：¥59.9（300 PM，永久有效）
- Pro：¥129（700 PM，永久有效）

## 关键限制与说明
- 多模型对比会按模型数倍增消耗
- 免费额度 24 小时重置，不累计
- 效果受音源质量与模型选择影响

## 技术与基础设施（简版）
- Next.js 16 + React 19 + TypeScript + Tailwind CSS v4
- BullMQ + Redis Worker 任务处理
- Tencent COS（S3 兼容）对象存储
- 模型：BS‑Roformer、Melband‑Roformer

## 相关链接
- 官网：https://keleeke.com/
- 定价：https://keleeke.com/pricing
- 核心工具（Stem Splitter）：https://keleeke.com/tools/stem-splitter
- 人声移除：https://keleeke.com/tools/remove-vocals
- Acapella 提取：https://keleeke.com/tools/acapella-extractor
