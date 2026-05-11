# Quarto Book Starter

這是用於建立 Quarto 書籍的範本，包含一些基本設定和範例內容。

## 使用說明

### 安裝

- [Quarto CLI](https://quarto.org/docs/get-started/)
- [Visual Studio Code](https://code.visualstudio.com/)
- [Visual Studio Code extension for Quarto](https://marketplace.visualstudio.com/items?itemName=quarto.quarto)

### 基本操作

```bash
# 檢查還需要安裝什麼工具
quarto check
# 預覽輸出，可以在瀏覽器裡面開啟預覽頁面
quarto preview
# 輸出檔案，會在專案根目錄 _output 資料夾裡面輸出 HTML、EPUB、PDF 格式的書籍檔案
quarto render
```

### 輸出

```bash
# 渲染所有格式
quarto render
# 渲染 HTML 格式
quarto render --to html
# 渲染 PDF 格式
quarto render --to pdf
# 渲染 EPUB 格式
quarto render --to epub
```

## 參考

- [Huan-Lin 學習筆記 - Quarto 筆記](https://www.huanlintalk.com/2025/09/quarto-first-impressions.html)
- [終究要有 Markdown 何不一開始就 Quarto?](https://windperson.github.io/Hello_World_devconf_2025-slide/docs/slides/web/#/title-slide)
- [Quarto 學習筆記](https://djhcod.github.io/Quarto-foundation.github.io/)
