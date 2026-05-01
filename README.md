# 晰黑體Ｂ５＆緻明體Ｂ５</br>XiHeiB5 & ZhiMingB5

「霞鶩晰黑」「霞鶩緻宋」相容 Windows 內置「細明體」度量版本，基於 IPA Gothic、IPA Mincho 衍生，採用 Big5-Eten 字集。

## 字型簡介

「晰黑體Ｂ５ / XiHeiB5」「緻明體Ｂ５ / ZhiMingB5」是[「霞鶩晰黑 MN」](https://github.com/lxgw/LxgwXiHei)[「霞鶩緻宋 MN」](https://github.com/lxgw/LxgwZhiSong)的分支版本，相容 Windows 系統「細明體」度量數據，採用 BIG5-Eten 字符集。可視為 Windows 系統「細明體」的開源度量相容（metric compatible）版本。

### 製作與調整

「晰黑體Ｂ５」和「緻明體Ｂ５」分別基於 IPA Gothic 和 IPA Mincho 衍生，在保留原字型等寬西文以及全寬基里爾字母、希臘字母的同時，將漢字和全形標點替換為「霞鶩晰黑 MN」和「霞鶩致宋 MN」的字形，並调整了收字範圍，使其符合 BIG5-Eten 字符集。

以下字圖參照主流廠商的 BIG5 繁體中文字型進行了調整（但並未增加修改後字圖真正對應的碼位映射）：

| 字元 | Unicode | BIG5 | 調整後字圖 |
|:----:|:----:|:----:|:----:|
| 嬔 | U+5B14 | 0xE955 | 嬎`U+ 5B0E` |
| 巕 | U+5DD5 | 0xF6DD | 𡿒`U+21FD2` |
| 獡 | U+7361 | 0xE67C | 𤡯`U+2486F` |
| 礡 | U+7921 | 0xF2A1 | 礴`U+ 7934` |

### 字彙
- 五大碼（BIG5）所收字元；
- 倚天（Eten）擴充漢字：碁銹裏墻恒粧嫺（在 CP950 中已有包含）；
- 倚天（Eten）私用區擴充字元，包括帶圈序號、小寫羅馬數字、日文假名、西里爾字母、「行列 40 輸入法」鍵位符等，部分字元增加 Unicode 正式碼位映射。

## 獲取字型

- 進入 [Releases](https://github.com/lxgw/XiZhiB5/releases) 頁面下載。

## 注意事項

「晰黑體Ｂ５」「緻明體Ｂ５」中的字元寬度與 Windows「細明體」的字元寬度並不完全相同，因此在替換文件內的 Windows「細明體」時仍可能出現部分字元跑位移動的情況。

### 已知問題
- 在 Word（Microsoft 365）中，豎排特性會失效，原因未知，見 #1。
- 已有使用者反饋，用本字型的硬替換版本替換系統字型後，Adobe Illustrator 等 Adobe 應用會顯示亂碼。如果您使用上述 Adobe 應用，請勿使用本字型替換系統預設字型。

## 授權資訊

- 本字型在 IPA 所開發併發布的 [IPA 字型](https://moji.or.jp/ipafont)基礎上衍生，依照 [IPA開放字型授權條款 第1.0版（IPA Font License 1.0）](https://opensource.org/licenses/IPA/) 授權。
- 您可以將本字型用於印刷品、數字文件、影視內容、海報廣告、包裝、出版物設計以及其他各種設計用途，包括商業和非商業用途；
  也可在本字型基礎上繼續改作衍生，惟衍生字型名稱（包括程式名、檔名、字型名）不得包含「IPA」字樣，且衍生字型須繼承相同授權許可（IPA Font License 1.0 與 SIL OFL 1.1 互不相容）。
- 根據 IPA Font License 1.0 有關條款，在沒有郵費、儲存媒介費用和手續費的情況下，須免費提供字型檔案，不得將字型檔案單獨售賣。
- 如果您要將本字型替換回 IPA 原始授權字型，請從 [IPA 字型 Ver.003.03 下載頁面](https://moji.or.jp/ipafont/ipa00303)獲取原始授權字型「IPA ゴシック」和「IPA 明朝」。  
  對於涉及字型檔案再分發的嵌入式應用（如應用程式、硬體裝置、網頁等嵌入），需要滿足 IPA 許可中針對衍生字型再分發的限制條件，[請點選此處](https://github.com/lxgw/LxgwNeoXiHei/blob/main/documentation/embedding_instructions.md)瞭解（跳轉到「霞鶩新晰黑」repo）。
- 有關 IPA Font License 1.0 的其他常見問題，請參閱 [FAQ（日語）](https://moji.or.jp/ipafont/faq)，需自備翻譯工具。
- 任何個人、企業、團隊等對本字型進行使用、複製、修改、分發等任意用途即視為您已完全閱讀、充分理解並同意 IPA Font License 1.0 授權協議。  
  「IPA 字型（IPA Font，IPAフォント）」為日本「獨立行政法人　資訊處理推進機構」（The Information-Technology Promotion Agency, “IPA”）的註冊商標。

## 參考資料

- [一點明體（新一細明體）](https://github.com/ichitenfont/I.Ming)
- [Takaoka Fonts](https://github.com/hidekatsu-izuno/takaoka-fonts)
