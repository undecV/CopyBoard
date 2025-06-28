# CopyBoard

一鍵複製，到處貼上

[English](README.md) | [正體中文](docs/README.zh_TW.md)

![CopyBoard](docs/screenshots/screenshot.png)

CopyBoard 是一個簡單的小工具，用於便捷快速的複製常用字串。

便攜僅一個檔案，可以離線運作，純 HTML/Javascript 無需 Import 其他模組。

- 支援分頁。
- 🆕 支援自動、明亮、和闇黑模式。
- 🆕 記憶色彩主題和上次的分頁。
- 🆕 支援行動裝置。

## 如何使用

1. 點選分頁按鈕切換分頁；
2. 點選對應的按鈕即可複製按鈕上的字串到剪貼簿。

## 定製

編輯 CopyBoard 的原始碼（以 txt 純文字檔方式開啟）；
在檔案的開頭不遠處，仿照格式編輯變數 `buttonMap`；
每個 Array 對應一組，每個 value 是一個按鈕；
儲存後重新整理網頁即可。

```javascript
var buttonMap = {
    "Some Tab"： [
        ["Foo", "Bar"],
        ["Bla bla bla..."]
    ], "Another Tab"： [
        ["A Lonely Button"]
    ]  // , ...
}
```

---

Reference:

- Color theme comes from [chriskempson/tomorrow-theme](https://github.com/chriskempson/tomorrow-theme) (MIT)
- A small part of CSS is borrowed from the [teacat/tocas](https://github.com/teacat/tocas) (MIT)
