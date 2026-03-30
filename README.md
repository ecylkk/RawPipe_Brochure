<p align="center">
  <img src="logo.png" alt="RawPipe" width="88" />
</p>

<h1 align="center">RawPipe</h1>

<p align="center">
  <strong>從快門到交付，一條管道搞定。</strong><br/>
  <sub>為攝影師 · 設計師 · 模特打造的自動化影像交付引擎</sub>
</p>

<!-- ═══════════════════════ 工業風格徽章區 ═══════════════════════ -->

<p align="center">
  <!-- 技術棧 -->
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" alt="Go" />
  <img src="https://img.shields.io/badge/Svelte-FF3E00?style=flat-square&logo=svelte&logoColor=white" alt="Svelte" />
  <img src="https://img.shields.io/badge/Cloudflare-F38020?style=flat-square&logo=cloudflare&logoColor=white" alt="Cloudflare" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/Tailwind%20CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind" />
</p>

<p align="center">
  <!-- 平台與狀態 -->
  <img src="https://img.shields.io/badge/Platform-Windows%20│%20macOS-1a1a2e?style=flat-square" alt="Platform" />
  <img src="https://img.shields.io/badge/Deploy-Single%20Binary-1a1a2e?style=flat-square" alt="Single Binary" />
  <img src="https://img.shields.io/badge/Mode-Offline--First-1a1a2e?style=flat-square" alt="Offline First" />
  <img src="https://img.shields.io/badge/License-Proprietary-1a1a2e?style=flat-square" alt="License" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Beta-0.7%20%22Silo%22-7c3aed?style=flat-square" alt="Version" />
</p>

---

<br/>

## 😩 你是不是也經歷過這些？

<table>
<tr>
<td width="33%" valign="top">

### 📸 攝影師

> *「拍完 2000 張 RAW，修完 200 張，然後花兩小時在微信上一張張傳給客戶選片…」*

- RAW 檔動輒 40MB+，手動導出費時費力
- 微信 / 網盤壓畫質，客戶看到的不是你調的色
- 「幫我把第 37 張再修一下」— 靠截圖溝通，來回磨
- 每次交付全靠人力，沒流程、沒記錄

</td>
<td width="33%" valign="top">

### 🎨 設計師

> *「PSD 源檔傳不了，導出 JPG 又怕客戶拿去亂改…」*

- PSD / AI 無法直接預覽，得逐個開 Photoshop 導出
- 版本管理全靠命名：`final_v2_改3_真的最終版.psd`
- 交付和日常聊天混在一起，找圖找到崩潰

</td>
<td width="33%" valign="top">

### 🧍 模特 / 客戶

> *「攝影師發了網盤連結，200 張圖下了半小時，選完又不知道怎麼告訴他…」*

- 下載等待，體驗糟糕
- 沒有「選片」功能，只能截圖或口頭描述
- 選完片沒有確認記錄，經常漏溝通

</td>
</tr>
</table>

<br/>

---

<br/>

## ⚡ RawPipe 怎麼解決

<table>
<tr>
<td width="50%">

### 📁 拖入即處理
把照片丟進資料夾，RawPipe 自動完成一切：
- **RAW / PSD / AI** → 智能提取嵌入預覽圖
- **JPG** → 長邊 2000px 高品質代理圖
- **SHA256 去重**，絕不重複處理

</td>
<td width="50%">

### ☁️ 秒級雲端交付
處理完成即刻自動上傳：
- 全球 CDN 邊緣節點，客戶秒開即看
- 私有桶存儲，搜索引擎抓不到
- 自動生成交付連結，一鍵分享

</td>
</tr>
<tr>
<td>

### ❤️ 愛心選片
客戶收到連結後在瀏覽器中直接操作：
- 瀑布流瀏覽，原色預覽不壓縮
- 點擊愛心標記喜歡的照片
- 選片結果自動保存，關頁面也不怕丟

</td>
<td>

### 🖥️ 實時監控面板
打開瀏覽器就能看到工作狀態：
- 處理進度、上傳狀態、Worker 負載一目了然
- 一個資料夾 = 一個項目，自動歸類
- 歷史記錄完整留存

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

## 📄 支持的檔案格式

| 類型 | 副檔名 |
|:-----|:-------|
| RAW | `.arw`  `.cr2`  `.cr3`  `.nef`  `.raf`  `.dng` |
| 設計 | `.psd`  `.ai` |
| 照片 | `.jpg`  `.jpeg` |

<br/>

---

<br/>

## 🚀 快速開始

1. 從 [Releases](https://github.com/ecylkk/RawPipe_Brochure/releases) 下載對應平台的可執行檔
2. 雙擊運行，打開 `http://localhost:9800` 查看面板
3. 把照片丟進 `watch_folder/`，RawPipe 自動處理 + 上傳
4. 將生成的交付連結發給客戶，客戶打開即選片

> 💡 單文件部署，離線優先。不需要 Docker、不需要資料庫安裝、不需要 Node.js。雙擊就跑。

<br/>

---

<br/>

## 🗺️ 產品路線

```
拖入照片 ──→ 智能提取 ──→ 雲端上傳 ──→ 生成連結 ──→ 客戶選片 ──→ 結果回傳
   │            │            │            │            │            │
   ▼            ▼            ▼            ▼            ▼            ▼
 watch_folder  ExifTool   Cloudflare    自動生成     ❤️ 愛心標記   攝影師收到
  自動偵測    + imaging      R2         分享 URL     瀑布流瀏覽    選片清單
```

<br/>

---

<br/>

## 🔒 關於本倉庫

本倉庫為 **RawPipe 產品宣傳頁**。核心原始碼為閉源商業軟體，不在此倉庫中。

如需試用或商業合作，請透過以下方式聯繫：

- 📧 Email: [kai@kaithe.world](mailto:kai@kaithe.world)
- 🌐 Website: [rawpipe.kaithe.world](https://rawpipe.kaithe.world)

<br/>

---

<p align="center">
  <sub>© 2026 Kai-Kai. All Rights Reserved.</sub><br/>
  <sub>Made with ☕ for creative professionals.</sub>
</p>
