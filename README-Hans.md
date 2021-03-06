[English](README.md) **简体中文** [繁體中文](README-Hant.md)

# 有爱黑体（《魔兽世界》字体包）

有爱黑体是《魔兽世界》和《魔兽世界：经典怀旧服》字体包，支持所有语言。有爱黑体是 [Noto Sans](https://github.com/googlei18n/noto-fonts) 和[思源黑体](https://github.com/adobe-fonts/source-han-sans)的合并字体。

> Make Love, Not Warcraft.<br>
> 要有爱，不要魔兽争霸。<br>
> 要愛，不要魔獸。

![有爱黑体](poster/heading.png)

![多语言支持](poster/multilingual.png)

## 下载指南

[GitHub 上的最新版](https://github.com/nowar-fonts/Nowar-Sans/releases)

镜像：[Gitee](https://gitee.com/nowar-fonts/Nowar-Sans)

有爱黑体有 5 种字重和 7 种地区变体，此外还有若干特性。

### 字重

* 300：细体
* 372：Normal
* 400：常规
* 500：中等
* 700：粗体
* ［Morpheus（西文标题字体）采用了更粗或更细的字重，以示强调。］

### 地区变体

CN、TW、HK、JP、KR 是 “标准变体”，支持完整的字符集，并遵循各地区的字形标准。

|    | 西文              | 简体中文     | 繁体中文 | 韩国语        |
| -- | ----------------- | ------------ | -------- | ------------- |
| CN | 中国大陆字形（UI）| 中国大陆字形 | 台湾字形 | 韩国字形（UI）|
| TW | 台湾字形（UI）    | 中国大陆字形 | 台湾字形 | 韩国字形（UI）|
| HK | 香港字形（UI）    | 中国大陆字形 | 香港字形 | 韩国字形（UI）|
| JP | 日本字形（UI）    | 中国大陆字形 | 台湾字形 | 韩国字形（UI）|
| KR | 韩国字形（UI）    | 中国大陆字形 | 台湾字形 | 韩国字形（UI）|

CL 是 “传统变体”，支持完整的字符集，采用传统印刷字形（即康熙字形）。

|     | 西文          | 中文     | 韩国语        |
| --- | ------------- | -------- | ------------- |
| CL  | 传统字形（UI）| 传统字形 | 传统字形（UI）|

GB 变体完全覆盖 GB 18030-2000 标准，移除了谚文支持，文件大小得以大幅缩减。

|    | 西文              | 中文         | 韩国语 |
| -- | ----------------- | ------------ | ------ |
| GB | 中国大陆字形（UI）| 中国大陆字形 | 不可用 |

* 西文：英语、西班牙语（拉丁美洲）、葡萄牙语、德语、西班牙语（欧洲）、法语、意大利语、俄语。
* 东亚语言：简体中文、繁体中文、韩国语。
* UI：中西文共用的标点视作西文标点；半角 CJK 标点。

### 特性

| 标记 | 名称        | 简介                                              |
| ---- | ----------- | ------------------------------------------------- |
| OSF  | Oldstyle    | 不齐线、不等宽的旧式数字。                        |
| SC   | Smallcaps   | 小型大写拉丁字母。                                |
| RP   | Roleplaying | `丶`（U+4E36）重映射为 `·`（U+00B7，MIDDLE DOT）。|

预编译的特性变体：`CL,OSF`、`CL,SC`、`CL,OSF,SC`、`GB,RP`。
