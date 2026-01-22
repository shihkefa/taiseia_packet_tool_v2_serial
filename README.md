# TaiSEIA 101 協定封包工具 v2.0 🌡️

[![GitHub Pages](https://img.shields.io/badge/GitHub%20Pages-Live-success)](https://shihkefa.github.io/taiseia_packet_tool_v2_serial/)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)

> 專為空調通訊協定開發設計的網頁版封包分析工具

## 🚀 快速開始

**直接使用線上版本，無需安裝：**

👉 [點擊這裡開啟 TaiSEIA 封包工具](https://shihkefa.github.io/taiseia_packet_tool_v2_serial/)
## 📖 專案簡介

這是我在開發空調模塊過程中製作的輔助工具，用於 TaiSEIA 101 協定的封包生成、解析與測試。現階段模塊開發已告一段落，特此分享給同樣需要進行空調通訊協定開發的朋友們使用。

### 🙏 特別感謝

在此非常感謝洋蔥大以及 Simon 大的 GitHub 相關文件，為本專案提供了重要的參考資料：

- **[tsunglung/taixia](https://github.com/tsunglung/taixia)** - TaiXia [TaiSEIA ® for ESPHome]
- **[xangin/TaiSEIA_ESPhome_samples](https://github.com/xangin/TaiSEIA_ESPhome_samples)** - Use TaiSEIA ESPhome in ESP32



## ✨ 主要功能

- 🔧 **封包生成器** - 快速生成符合 TaiSEIA 101 協定的控制封包
- 🔍 **封包解析器** - 即時解析接收到的封包內容
- 📊 **參數調整** - 支援溫度、風速、模式等參數設定
- 💾 **序列埠通訊** - 透過 Web Serial API 與實體設備通訊
- 📝 **記錄功能** - 完整記錄通訊歷程，方便除錯分析

## 🛠️ 技術特點

- 純網頁實現，無需安裝任何軟體
- 基於 Web Serial API，支援直接與串口設備通訊
- 即時互動介面，操作簡便直觀
- 完整的協定封包處理邏輯

## 📌 使用說明

1. 使用 Chrome、Edge 或其他支援 Web Serial API 的瀏覽器開啟工具
2. 連接你的串口設備
3. 選擇對應的串口參數（波特率、資料位元等）
4. 開始發送或接收封包

## ⚠️ 注意事項

- 工具目前已滿足我個人的空調模塊開發需求
- 可能存在一些小缺失或待優化的地方
- **短期內不會進行大幅更新**，但歡迎提出問題或建議

## 🤝 貢獻

如果你發現任何問題或有改進建議，歡迎：
- 提交 [Issue](https://github.com/shihkefa/taiseia_packet_tool_v2_serial/issues)
- 發起 Pull Request

## 📄 授權

本專案採用 MIT 授權條款 - 詳見 [LICENSE](LICENSE) 文件

## 👨‍💻 作者

**Kefa Shih**
- GitHub: [@shihkefa](https://github.com/shihkefa)

---

<div align="center">

**如果這個工具對你有幫助，歡迎給個 ⭐ Star！**

Made with ❤️ for HVAC developers

</div>
