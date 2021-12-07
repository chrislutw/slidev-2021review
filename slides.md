---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## 2021 年 回顧與未來展望
# persist drawings in exports and build
drawings:
  persist: false
---

# 2021年 回顧與未來展望

技術服務部 網頁組 呂正中

---
layout: two-cols
---

# 回顧 2021 年 目標

去年給自己的目標

- <logos-vue /> Vue 3 準備接軌
- <logos-cypress /> 自動測試導入
- <logos-tailwindcss-icon /> 有效且組織化管理CSS(Tailwind)

<br />
<br />

# 目標達成率

實際工作達成1項，但也持續關注動態

<div class="text-8xl">33%</div>

::right::
# 實際產出

工單系統已有詳細清單，整理出以下為精華

- <logos-nuxt-icon /><logos-tailwindcss-icon /> **金銀島歷程** - 網站改版 aspx → nuxt2
- <vscode-icons-file-type-elastic /> **ELK 平台** - 收集伺服器 Log 到平台上
- <logos-vue /> **Admin2後端工具** - 網站改版 aspx → vue2


<br />
<br />

# 自我提升

持續追大神帳號關注前端技術發表

- twitter - @youyuxi, @antfu7, @Atinux, @debs_obrien, @addyosmani, @_piO_
- 線上研討會 - VueConf Toronto 2021, Nuxt Nation 2021, Chrome Dev Summit 2021


<!--
You can have `style` tag in markdown to override the style for the current page.
Learn more: https://sli.dev/guide/syntax#embedded-styles
-->

<style>
h1 {
  background-color: #2B90B6;
  background-image: linear-gradient(45deg, #4EC5D4 10%, #146b8c 20%);
  background-size: 100%;
  -webkit-background-clip: text;
  -moz-background-clip: text;
  -webkit-text-fill-color: transparent;
  -moz-text-fill-color: transparent;
}
</style>

---

# <logos-nuxt-icon /><logos-tailwindcss-icon />金銀島歷程改版內容

此次改版有很多亮眼的功能，節省很多開發時間

### 功能

|     |     |
| --- | --- |
| `<static-img />` 圖片基礎元件 | 多語系圖片容錯為網站預設語系 |
| <logos-tailwindcss-icon /> 原子化 CSS(Atomic CSS) | 複製元件時只需要 `.vue` 檔|
| 多樣化的打包部署方式 | SSR、SPA、ISG、<kbd><span class="text-red-400">Static</span></kbd> 部署至任意伺服器 |
| 累積 2x 種共用基礎元件 | 修改大量頁面時減少維護成本 |
| PlayGround | 人員測試、調整、製作元件樣式或範例 |
| 多專案發佈 | 同一份原碼，不同的環境設定 |

---
layout: image-right
image: https://source.unsplash.com/collection/94734566/1920x1080
---

# 未達成目標

> <logos-vue /> Vue 3 準備接軌

<br>

- 去年剛出社群資源尚未穩定
- nuxt 3 開源專案尚未完成開發
- Admin2 el-element-admin 專案，直接遷移至 vue3 版本有難度

---
layout: image-right
image: https://source.unsplash.com/collection/94734566/1920x1080
---

# 未達成目標

> <logos-cypress /> 自動測試導入

<br>

- 疫情關係報名的課程沒報到
- 有先預習課程推薦書藉「單元測試的藝術-第二版」

---

# 2022 年 新目標

去年的經驗讓我發現目標訂太大、太多，實際執行有難度，今年以下列2項為主

<br>
<br>

## 去年的目標 - <logos-cypress />自動測試導入

<br>
<br>

## 前端多媒體資源分離 - <logos-cloudinary />可程式化的圖片媒體資源


<br>
<br>
<br>
<br>

# 次要目標

在主要目標達成情況下，有餘力才執行
## Vue 3 準備接軌  - Admin2 <logos-vue /> vue3 導入

---

<div class="grid gap-4 grid-cols-2">
<div>

# <logos-cypress /> 自動測試導入

不累積測試項目，會讓你的專案充滿不確定性，無法評估改動時程

- 痛是一時的，導入的必經之路
- 不求測試覆蓋率，而是測試項目與開發時程的甜密點
- 金銀島年度計劃 - 穩定的後勤補給

## 預期效益

- 減少出包機率
- 再也不怕改東壞西
- 減少品檢負擔
- 開發時會養成好習慣

</div>
<div class="myimage">
</div>
</div>



<style>
  .myimage {
    background-image: url(https://i.ytimg.com/vi/UFErY92HeyM/maxresdefault.jpg);
    background-position: center;
    background-size: contain;
    background-repeat: no-repeat;
  }
</style>

---
layout: image-right
image: /cloudinary-interface.png
---
# <logos-cloudinary />可程式化的圖片媒體資源

- 可程式化的圖片路徑
- 可線上直接編輯圖片、並有眾多插件可供使用
- 有圖片管理上傳後台介面、API、統計資料
- 支援 gcs, s3 CDN 存儲

## 預期效益

- git 切換分支、打包、發佈速度提升加速
- 可依客戶裝置提供加載不同實際大小圖片，加快載入速度
- 編輯效果可以儲存腳本，運營人員也能無痛調整

---
layout: image
image: https://www.astralweb.com.tw/wp-content/uploads/2018/12/Cloudinary-Introduction-4.png
class: ~ !bg-contain
---
---

# Admin2 <logos-vue /> vue3 導入

## 痛點

- 現行的後端網站 mixin 功能，無法高度客製頁面需求
- 開發製作邏輯、流程、畫面都綁著 mixin ，開發者往往要爬完 1000 行才能知其運作細節
- Admin2 `el-element-admin` 專案，直接遷移至 vue3 版本有難度

## 已知的新舊站整合 BUG

- 舊站把 `query` 當作頁面的 `path` 在使用，導致新站鑲嵌舊站時發生找不到頁面問題
- 新站鑲嵌舊站時，從舊站開啟新站的連結(無另開視窗)，會發生無限堆疊的鑲嵌情況

## 建議改善方案

- Vue 3 組合式 API 重構邏輯、流程、畫面，分層分類
- 重新套用 [element-plus-admin](https://element-plus-admin.hsianglee.cn/) 專案 [<logos-github-icon>](https://github.com/hsiangleev/element-plus-admin)
- 建議新舊站不要鑲嵌