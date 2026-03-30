<p align="center">
  <img src="logo.png" alt="RawPipe" width="88" />
</p>

<h1 align="center">RawPipe</h1>

<p align="center">
  <strong>從快門到交付，一條管道搞定。</strong><br/>
  <sub>為攝影師 · 設計師 · 模特打造的自動化影像交付引擎</sub>
</p>

<!-- ═══════════════════════ 技術棧徽章 ═══════════════════════ -->

<p align="center">
  <img src="https://img.shields.io/badge/Go-72.6%25-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Svelte-14.0%25-FF3E00?style=flat-square&logo=svelte&logoColor=white" alt="Svelte" />
  <img src="https://img.shields.io/badge/JavaScript-6.3%25-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/CSS-3.0%25-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS" />
  <img src="https://img.shields.io/badge/HTML-2.2%25-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML" />
  <img src="https://img.shields.io/badge/Shell-0.9%25-4EAA25?style=flat-square&logo=gnubash&logoColor=white" alt="Shell" />
</p>


<!-- ═══════════════════════ 狀態徽章 ═══════════════════════ -->

<p align="center">
  <img src="https://img.shields.io/badge/Platform-Windows%20│%20macOS-1a1a2e?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/badge/Deploy-Single%20Binary-1a1a2e?style=flat-square" alt="Single Binary" />
  <img src="https://img.shields.io/badge/Mode-Offline--First-1a1a2e?style=flat-square" alt="Offline First" />
  <img src="https://img.shields.io/badge/License-Proprietary-1a1a2e?style=flat-square" alt="License" />
  <img src="https://img.shields.io/badge/Beta-0.7%20%22Silo%22-7c3aed?style=flat-square" alt="Version" />
</p>

---

<br/>

## 🎯 RawPipe 能幫你做什麼

<table>
<tr>
<td width="33%" valign="top">

### 📸 攝影師

你只管拍和修，剩下的交給 RawPipe：

- ✅ **自動處理 RAW 檔** — 丟進資料夾，自動提取預覽圖
- ✅ **秒級交付** — 處理完即上傳雲端，生成交付連結
- ✅ **告別微信傳圖** — 不壓畫質，客戶看到的就是你調的色
- ✅ **選片不再靠截圖** — 客戶用❤️標記，結果自動回傳

</td>
<td width="33%" valign="top">

### 🎨 設計師

源檔不用傳，預覽一鍵送達：

- ✅ **PSD / AI 自動預覽** — 不用開 Photoshop 也能看
- ✅ **獨立交付通道** — 不跟日常聊天混在一起
- ✅ **版本不再靠命名** — 一個項目一個資料夾，自動歸類
- ✅ **源檔安全** — 客戶只能看預覽圖，拿不到原始檔

</td>
<td width="33%" valign="top">

### 🧍 模特 / 客戶

打開連結就能選片，零門檻：

- ✅ **不用下載** — 瀏覽器直接看，秒開不等待
- ✅ **愛心選片** — 喜歡就點❤️，直覺操作
- ✅ **自動保存** — 關掉頁面也不怕，選的片子都還在
- ✅ **原色預覽** — 不壓縮、不變色，所見即所得

</td>
</tr>
</table>

<br/>

---

<br/>

## ⚡ 核心功能

<table>
<tr>
<td width="50%">

### 📁 拖入即處理
把照片丟進資料夾，RawPipe 自動完成一切：
- **RAW** (`.arw` `.cr2` `.cr3` `.nef` `.raf` `.dng`) → 智能提取嵌入預覽圖
- **設計稿** (`.psd` `.ai`) → 自動提取縮略圖
- **照片** (`.jpg` `.jpeg`) → 長邊 2000px 高品質代理圖
- **SHA256 去重**，絕不重複處理

</td>
<td width="50%">

### ☁️ 秒級雲端交付
處理完成即刻自動上傳：
- Cloudflare R2 全球邊緣節點，客戶秒開即看
- 私有桶存儲，搜索引擎抓不到你的作品
- 自動生成交付連結，一鍵發給客戶
- 多租戶隔離，每位客戶的檔案互不可見

</td>
</tr>
<tr>
<td>

### ❤️ 愛心選片
客戶收到連結後在瀏覽器中直接操作：
- 瀑布流瀏覽，原色預覽不壓縮
- 點擊❤️標記喜歡的照片
- 選片結果自動保存，關頁面也不丟
- 無需註冊、無需下載，零門檻

</td>
<td>

### 🖥️ 實時監控面板
打開瀏覽器就能看到工作狀態：
- 處理進度、上傳狀態、Worker 負載一目了然
- 一個資料夾 = 一個項目，自動歸類
- 歷史記錄完整留存
- 嵌入式面板，不需要額外安裝

</td>
</tr>
</table>

<br/>

---

<br/>

## 🏆 為什麼選 RawPipe

| | 傳統方式 | RawPipe |
|:---|:---------|:--------|
| **交付速度** | 手動導出 + 上傳網盤 *(30min+)* | 拖入即交付 *(全自動)* |
| **畫質保真** | 微信壓縮 / 網盤限速 | 原色預覽，全球 CDN 加速 |
| **選片體驗** | 截圖 + 口頭描述 | ❤️ 一鍵愛心，記錄留存 |
| **RAW 支持** | 手動開軟體導出 | 自動提取嵌入預覽 |
| **PSD / AI** | 必須裝 Adobe 才能看 | 自動提取，瀏覽器直看 |
| **多客戶管理** | 全靠命名大法 | 邀請制 · 多租戶隔離 |
| **部署方式** | 安裝一堆依賴 | **雙擊一個檔案，搞定** |

<br/>

---

<br/>

## 🚀 快速開始

```
1. 下載  →  從 Releases 下載對應平台的可執行檔
2. 雙擊  →  打開 http://localhost:9800 查看面板
3. 丟圖  →  把照片放進 watch_folder/
4. 分享  →  將生成的交付連結發給客戶
```

> 💡 **單文件部署，離線優先。** 不需要 Docker、不需要資料庫、不需要 Node.js。雙擊就跑。

<br/>

---

<br/>

## 🗺️ 工作流程

```
 你的照片          RawPipe 自動處理            客戶端

 ┌─────────┐      ┌──────────────┐      ┌──────────────┐
 │  拖入    │─────→│  智能提取    │─────→│  打開連結    │
 │  照片    │      │  代理圖      │      │  瀏覽選片    │
 └─────────┘      └──────┬───────┘      └──────┬───────┘
                         │                      │
                         ▼                      ▼
                  ┌──────────────┐      ┌──────────────┐
                  │  雲端上傳    │      │  ❤️ 愛心標記  │
                  │  生成連結    │      │  結果回傳     │
                  └──────────────┘      └──────────────┘
```

<br/>

---

<br/>

## 🔒 關於本倉庫

本倉庫為 **RawPipe 產品宣傳頁**。核心原始碼為閉源商業軟體，不在此倉庫中。

如需試用或商業合作，請聯繫：

- 📧 Email: [kai@kaithe.world](mailto:kai@kaithe.world)

<br/>

---

<p align="center">
  <sub>© 2026 Kai-Kai. All Rights Reserved.</sub><br/>
  <sub>Made with ☕ for creative professionals.</sub>
</p>
