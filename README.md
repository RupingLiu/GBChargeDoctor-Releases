<div align="center">

# GBChargeDoctor 发布下载

**面向 GB/T 充电通信轨迹的协议级诊断工具**

Windows 安装包、自动更新清单与签名文件公开分发通道。

[![最新版本](https://img.shields.io/github/v/release/RupingLiu/GBChargeDoctor-Releases?label=release&color=00B3FF&style=for-the-badge)](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/latest)
[![平台](https://img.shields.io/badge/platform-Windows-0F172A?style=for-the-badge&logo=windows11&logoColor=white)](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/latest)
[![离线核心](https://img.shields.io/badge/core-%E7%A6%BB%E7%BA%BF%E5%88%86%E6%9E%90-10B981?style=for-the-badge)](#安全性与离线使用)
[![本地数据](https://img.shields.io/badge/data-%E6%9C%AC%E5%9C%B0%E6%96%87%E4%BB%B6-22C55E?style=for-the-badge)](#安全性与离线使用)
[![Tauri 更新](https://img.shields.io/badge/tauri-updater-24C8DB?style=for-the-badge&logo=tauri&logoColor=white)](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/latest/download/latest.json)
[![源码状态](https://img.shields.io/badge/source-%E7%A7%81%E6%9C%89-64748B?style=for-the-badge)](#仓库定位)

[![下载 Windows 安装包](https://img.shields.io/badge/%E4%B8%8B%E8%BD%BD-Windows%20%E5%AE%89%E8%A3%85%E5%8C%85-00B3FF?style=for-the-badge&logo=github&logoColor=white)](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/download/v0.5.2/GBChargeDoctor_0.5.2_x64-setup.exe)

[简体中文](#简体中文) / [繁體中文](#繁體中文) / [English](#english)

</div>

---

## 简体中文

GBChargeDoctor 是面向 GB/T 27930 充电通信数据的诊断工具。本仓库用于公开发布 Windows 安装包、自动更新清单和更新签名，便于用户下载安装与版本更新。

## 界面预览

<div align="center">
  <img src="assets/gbcharge-doctor-workbench.png" alt="GBChargeDoctor 软件界面截图" width="100%">
</div>

## 如何使用

| 步骤 | 操作 | 说明 |
| --- | --- | --- |
| 1 | 下载安装 | 从本页下载 Windows 安装包并完成安装。 |
| 2 | 导入轨迹 | 点击右上角“导入”，选择本地 CSV、TXT、ASC、BLF 或 SocketCAN PCAP 轨迹文件。 |
| 3 | 选择协议 | 默认使用“自动识别”；也可以手动选择 GB/T 27930-2015、GB/T 27930-2023 或 GB/T 27930.2-2024。 |
| 4 | 查看诊断 | 导入后软件会自动完成分析，并展示结论、问题列表、阶段信息和证据帧。 |
| 5 | 生成报告 | 点击“报告”，在本机生成分析报告预览，用于存档、沟通或测试记录。 |

## 发布通道

| 通道 | 文件 | 链接 |
| --- | --- | --- |
| 稳定版 | Windows 安装包 | [GBChargeDoctor_0.5.2_x64-setup.exe](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/download/v0.5.2/GBChargeDoctor_0.5.2_x64-setup.exe) |
| 稳定版 | 版本发布页 | [GBChargeDoctor 0.5.2](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/tag/v0.5.2) |
| 自动更新 | 更新清单 | [latest.json](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/download/v0.5.2/latest.json) |
| 自动更新 | 更新签名 | [GBChargeDoctor_0.5.2_x64-setup.exe.sig](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/download/v0.5.2/GBChargeDoctor_0.5.2_x64-setup.exe.sig) |

## 安全性与离线使用

本仓库只提供安装包，不公开源码。GBChargeDoctor 的核心诊断流程面向本地使用：用户在自己的电脑上导入充电通信/CAN 轨迹文件，软件在本机完成协议解析、规则分析和报告生成。

| 范围 | 说明 |
| --- | --- |
| 离线分析 | 核心导入、分析和报告功能不依赖云端服务，可在离线环境中使用。 |
| 本地数据 | 用户导入的轨迹文件保留在本机，软件不会为了分析而上传这些文件。 |
| 联网边界 | 网络访问主要用于可选的版本检查，以及从 GitHub Releases 下载更新包。 |
| 更新校验 | 每个发布版本会提供 Tauri 更新清单和更新签名，用于自动更新流程校验。 |
| 下载来源 | 建议只从本仓库或发布方提供的官方渠道下载安装包。 |

## 仓库定位

本仓库只作为 GBChargeDoctor 的公开二进制分发通道，托管安装包、更新清单、更新签名和产品截图。产品源码仓库保持私有，本仓库不包含源码，也不授予源码使用权。

---

## 繁體中文

GBChargeDoctor 是面向 GB/T 27930 充電通訊資料的診斷工具。本儲存庫用於公開發布 Windows 安裝程式、自動更新清單與更新簽章，方便使用者下載安裝與版本更新。

### 介面預覽

<div align="center">
  <img src="assets/gbcharge-doctor-workbench.png" alt="GBChargeDoctor 軟體介面截圖" width="100%">
</div>

### 如何使用

| 步驟 | 操作 | 說明 |
| --- | --- | --- |
| 1 | 下載安裝 | 從本頁下載 Windows 安裝程式並完成安裝。 |
| 2 | 匯入軌跡 | 點擊右上角「導入」，選擇本機 CSV、TXT、ASC、BLF 或 SocketCAN PCAP 軌跡檔案。 |
| 3 | 選擇協議 | 預設使用「自動識別」；也可以手動選擇 GB/T 27930-2015、GB/T 27930-2023 或 GB/T 27930.2-2024。 |
| 4 | 查看診斷 | 匯入後軟體會自動完成分析，並顯示結論、問題列表、階段資訊與證據幀。 |
| 5 | 產生報告 | 點擊「報告」，在本機產生分析報告預覽，用於存檔、溝通或測試記錄。 |

### 快速下載

| 項目 | 連結 |
| --- | --- |
| Windows 安裝程式 | [GBChargeDoctor_0.5.2_x64-setup.exe](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/download/v0.5.2/GBChargeDoctor_0.5.2_x64-setup.exe) |
| 版本發布頁 | [GBChargeDoctor 0.5.2](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/tag/v0.5.2) |
| 自動更新清單 | [latest.json](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/download/v0.5.2/latest.json) |
| Tauri 更新簽章 | [GBChargeDoctor_0.5.2_x64-setup.exe.sig](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/download/v0.5.2/GBChargeDoctor_0.5.2_x64-setup.exe.sig) |

### 安全性與離線使用

本儲存庫只提供安裝程式，不公開原始碼。GBChargeDoctor 的核心診斷流程面向本機使用：使用者在自己的電腦上匯入充電通訊/CAN 軌跡檔案，軟體在本機完成協議解析、規則分析與報告產生。

| 範圍 | 說明 |
| --- | --- |
| 離線分析 | 核心匯入、分析與報告功能不依賴雲端服務，可在離線環境中使用。 |
| 本機資料 | 使用者匯入的軌跡檔案保留在本機，軟體不會為了分析而上傳這些檔案。 |
| 連網邊界 | 網路存取主要用於可選的版本檢查，以及從 GitHub Releases 下載更新包。 |
| 更新校驗 | 每個發布版本會提供 Tauri 更新清單與更新簽章，用於自動更新流程校驗。 |
| 下載來源 | 建議只從本儲存庫或發布方提供的官方通道下載安裝程式。 |

### 說明

本儲存庫僅作為公開分發通道，不包含原始碼，也不授予原始碼使用權。GBChargeDoctor 的原始碼儲存庫保持私有。

---

## English

GBChargeDoctor is a diagnostic tool for GB/T 27930 charging communication data. This repository publicly publishes the Windows installer, updater metadata, and update signature so users can install and receive version updates.

### Interface Preview

<div align="center">
  <img src="assets/gbcharge-doctor-workbench.png" alt="GBChargeDoctor software interface screenshot" width="100%">
</div>

### How to Use

| Step | Action | Description |
| --- | --- | --- |
| 1 | Install | Download the Windows installer from this page and complete installation. |
| 2 | Import trace | Click "导入" in the upper-right corner and select a local CSV, TXT, ASC, BLF, or SocketCAN PCAP trace file. |
| 3 | Choose protocol | Keep Auto Detect by default, or manually select GB/T 27930-2015, GB/T 27930-2023, or GB/T 27930.2-2024. |
| 4 | Review diagnostics | After import, the application analyzes automatically and shows the verdict, findings, phase information, and evidence frames. |
| 5 | Generate report | Click "报告" to generate a local report preview for archiving, communication, or test records. |

### Quick Download

| Item | Link |
| --- | --- |
| Windows installer | [GBChargeDoctor_0.5.2_x64-setup.exe](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/download/v0.5.2/GBChargeDoctor_0.5.2_x64-setup.exe) |
| Release page | [GBChargeDoctor 0.5.2](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/tag/v0.5.2) |
| Updater metadata | [latest.json](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/download/v0.5.2/latest.json) |
| Tauri update signature | [GBChargeDoctor_0.5.2_x64-setup.exe.sig](https://github.com/RupingLiu/GBChargeDoctor-Releases/releases/download/v0.5.2/GBChargeDoctor_0.5.2_x64-setup.exe.sig) |

### Security and Offline Use

This repository provides installer artifacts only; the source code is not public. GBChargeDoctor's core diagnostic workflow is local-first: users import charging communication/CAN trace files on their own machine, and the application performs protocol parsing, rule analysis, and report generation locally.

| Area | Description |
| --- | --- |
| Offline analysis | Core import, analysis, and report features do not depend on a cloud service and can be used in an offline environment. |
| Local data | Imported trace files remain on the user's machine and are not uploaded by the application for analysis. |
| Network boundary | Network access is mainly used for optional update checks and downloading update packages from GitHub Releases. |
| Update verification | Each release provides Tauri updater metadata and an update signature for the automatic update flow. |
| Download source | Download installers only from this repository or an official channel provided by the publisher. |

### Notice

This repository is a public distribution channel only. It does not contain source code and does not grant source-code usage rights. The GBChargeDoctor source repository remains private.