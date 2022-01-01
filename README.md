# rime-kz-experiment

哈萨克语拼音化简化实验性方案

## 前言概述

PC 端的哈萨克语老文字键入还是挺麻烦的, 哈萨克语文字存在老文字(中国新疆境内)、哈萨克斯坦(西里尔文字、拉丁化文字)等多种形式, 并且存在 RTL 和 LTR 的排版问题, 本仓库为哈萨克语文字输入的拼音化简化方案实验, 旨在统一哈萨克语输入不同文字类型的输入。

本仓库基于 [GPL v3](./LICENSE) 开源, 请遵守开源协议!

## 拼音化方案

哈萨克语属于拼音文字, 本仓库是基于 [Rime 输入法](https://github.com/rime) 的一次语言文字实验, 本仓库的实验性文字对照表结合了多种语言发声、国际音标等多种方案。

> 需要注意的是: 哈萨克斯坦并没有完成确定哈语拉丁化的方案, 无法使用 Unicode 对哈语新拉丁化字母进行标准化。比如 `gh` 这个音, TeX 的写法为 `\'G`。因此, 这里提到的拉丁化方案并不完整与准确, 相关讨论可见知乎问题 [如何评价哈萨克斯坦拉丁化哈萨克文字母表？](https://www.zhihu.com/question/65270788)

| 拼音方案 | 老文字 | 西里尔字母 | 拉丁化方案 |
| -------- | ------ | ---------- | ---------- |
| a        | ا      | А а        | A a        |
| ae       | ٴا     | Ә ә        | Á á        |
| b        | ب      | Б б        | B b        |
| d        | د      | Д д        | D d        |
| e        | ى      | Ы ы        | Y y        |
| ie       | ە      | Е е        | E e        |
| ue       | ٴى     | І і        |            |
| f        | ف      | Ф ф        | F f        |
| g        | گ      | Г г        | G g        |
| gh       | ع      | Ғ ғ        |            |
| h        | ح      | Х х        | H h        |
| hh       | ھ      | Һ һ        | H h        |
| i        | ي      | Й й        |            |
| j        | ج      | Ж ж        | J j        |
| k        | ك      | К к        | K k        |
| l        | ل      | Л л        | L l        |
| m        | م      | М м        | M m        |
| n        | ن      | Н н        | N n        |
| ng       | ڭ      | Ң ң        | Ń ń        |
| o        | و      | О о        | O o        |
| oe       | ٶ      | Ө ө        | Ó ó        |
| p        | پ      | П п        | P p        |
| q        | ق      | Қ қ        | Q q        |
| r        | ر      | Р р        | R r        |
| s        | س      | С с        | S s        |
| t        | ت      | Т т        | T t        |
| u        | ۇ      | Ұ ұ        | U u        |
| iu       | ٷ      | Ү ү        | Ú ú        |
| v        | ۆ      | В в        | V v        |
| w        | ۋ      | У у        | Ý ý        |
| z        | ز      | З з        | Z z        |
| sh       | ش      | Ш ш        | Sh sh      |
| ch       | چ      | Ц ц        | Ch ch      |

- 西里尔哈萨克语独有的字母 (老文字不含)

| 拼音方案 | 老文字 | 西里尔字母 | 拉丁化方案 |
| -------- | ------ | ---------- | ---------- |
| io       | --     | Ё ё        |            |
| --       | --     | И и        |            |
| --       | --     | Ч ч        |            |
| --       | --     | Щ щ        |            |
| --       | --     | Ъ ъ        |            |
| --       | --     | Ь ь        |            |
| --       | --     | Э э        |            |
| --       | --     | Ю ю        |            |
| --       | --     | Я я        |            |

## References

- [Unicode 码表](https://blog.csdn.net/hherima/article/details/9045765)
- [哈萨克语 Wikipedia](https://zh.wikipedia.org/wiki/%E5%93%88%E8%96%A9%E5%85%8B%E8%AA%9E)
- [漫谈：哈萨克文字母、字体、输入法及其他](https://zhuanlan.zhihu.com/p/98359081)
- [Rime 輸入方案設計書](https://github.com/rime/home/wiki/RimeWithSchemata)
- [如何评价哈萨克斯坦拉丁化哈萨克文字母表？](https://www.zhihu.com/question/65270788)
