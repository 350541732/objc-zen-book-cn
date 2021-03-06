# ObjC Zen Book 中文翻译（禅与 Objective-C 编写的艺术）


![](./images/zen-logo-thumb.png)

[ObjC Zen Book 原始链接](https://github.com/objc-zen/objc-zen-book)


ObjC Zen Book 非常棒，是对 Objective-C 语言程序书写的进阶佳作，相比于其他风格指南，本书正如作者介绍的：

> 现在虽然有很多指南，但是它们都是存在一些问题的。我们不想介绍一些死板的规定，我们想提供一个在不同开发者之间能达成一致的写代码的方法。随时间的推移，这本书开始转向面向如何设计和构建优秀的代码。

之前没有在网上看到相关的翻译，所以我希望能够通过翻译此书，惠及国内开发者朋友，同时也是对自己的锻炼。水平浅薄，有所不足之处请在 issue 批评指正，也欢迎各位朋友来贡献翻译。 

/translation 文件夹下是翻译过程中为了分出来的章节，*已经废弃*

**如果有更好的修订和句子请直接 fork 本仓库，在 README.md 文件中修改，并申请 pull request 到 <https://github.com/oa414/objc-zen-book-cn/>。**

**本译文已取得原文作者授权允许翻译，并且将在进一步校对后，以 Fork 原仓库方式提交中文翻译的形式合并到官方仓库**

## 翻译标准

为了追求中文通顺，不影响原文意思的情况下，部分内容可能会改变一些描述，或者去掉一些英文的难以翻译的幽默。

此外，一些技术名词的翻译，可能没有明确的标准，但是会追求在这本小书内的统一，翻译的对应名词表格：

|中文  | 英文 | 
| ----- | --------| 
|分类 | Categories |
|协议 | Protocols |
|接口 | interface |
|实践 | practice |
|签名 | signature |


##  排版规范和注意事项



- 参考 <https://github.com/objccn/articles/wiki/%E5%A6%82%E4%BD%95%E8%B4%A1%E7%8C%AE%E5%86%85%E5%AE%B9>

- 文章标题使用 \# 标记
章节标题从 \#\# 标记开始使用，按照层次每层增加一级，即 \#\#，\#\#\# 等。
代码可以在代码内容每行前使用四个空格开始，或是在代码顶格开始并前后使用三个 \`\`\` 符号。注意两种方式不要混用，另外无论使用哪种方式，代码缩进为4个空格。一行太长的代码（包括缩进80个字符以上）请注意在合适的地方进行换行和对齐。

- 较为专业术语请保留英文原文，特别是对于普遍习惯使用的短语或者英文内容更容易理解的词。比如，虽然有很多人将 Key Value Observing 翻译为 键值观察，但是应该更偏向于选择 KVO 这样通用的缩略形式。另外，千万不要将诸如 Grand Central Dispatch 翻译为大中枢派发之类的闻所未闻的叫法，请将其简单地写作 GCD 即可。

- 中文和英文混编时，如果一个英文单词/短语前后是中文字符，请留意随手在英文和中文之间留出一个半角空格，就像上面这条中做的这样

- 中文正文及标题中出现的英文及数字应该使用半角方式输入，并且在左右各留一个半角空格。如果这些这些半角英文及数字的左边或者右边紧接着任何的中文全角括号或者其他标点符号的话，则不需要加入半角空格。
代码中的注释我们希望您也能顺手进行翻译。


## 进度

已经完成所有的翻译并做了自我校对。

## 作者

原作者：

**Luca Bernardi**

- http://lucabernardi.com
- @luka_bernardi
- http://github.com/lukabernardi

**Alberto De Bortoli**

- http://albertodebortoli.com
- @albertodebo
- http://github.com/albertodebortoli

翻译和校队：

- 林翔宇 linxiangyu@nupter.org
- 庞博 bopang@sohu-inc.com


