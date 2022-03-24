# 史記 Typesetting using Antique Style

## 史記

《史記》是中國的一部紀傳體史書，一般認爲由西漢武帝時期任職太史令的司馬遷繼承父親司馬談遺志所編寫。

史記 (Shiji), a.k.a. Records of the Grand Historian, is a monumental history of ancient China and the world finished around 94 BC by the Western Han Dynasty historian 司馬遷 (Sima Qian) after having been started by his father, 司馬談 (Sima Tan).

### 史記會注考證

《史記會注考證》是日本學者瀧川資言（龜太郎）對《史記》所作的集注與考訂。

## 排版 ShiJiAntiqueStyle

基於upTeX與[jlreq](https://github.com/abenori/jlreq)提供的功能將文本清樣進行仿古風格的中文直排。通過 JFM 設定實現了行間句讀符號。利用[gezhu](https://github.com/yang-le/gezhu)實現了割注，這個宏包似乎比jlreq内附的warichu功能更為適應仿古排版。仿武英殿二十四史本，利用[TikZ](https://github.com/pgf-tikz/pgf)繪製了欄綫。

正文字體使用了[FontForge](https://github.com/fontforge/fontforge)魔改的[源流明體](https://github.com/ButTaiwan/genryu-font)。包括縮放字形、長體的製作、繪製特殊記號等等。

## 文本來源

見 Text Contents for 史記。

## 檔案結構
```
 WorkSpace
    ├─Contents
    │ ├─chapter*.tex
    │ └─notes*.tex
    └─Style
      └─main.tex
```
