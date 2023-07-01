[https://github.com/Natumsol/obsidian-pangu](https://github.com/Natumsol/obsidian-pangu) 的魔改版本，在添加中英文空格的基础上启用了原 pangu 的「统一文本内标点的使用」并自己添加了一些规则。

插件的任何可取之处均来自原作者 [https://github.com/natumsol](https://github.com/natumsol)。

细节不完善（PS：英文效果尤其不好），大家可以自取调教。= = 有建议可以提 issue.

使用：下载 release 1.0.0 里的 pangu-go.zip，解压到 `.obsidian/plugins`，设置里启用！

## 效果

尚未把格式化规则全列出来，感兴趣的可以试用或看代码……以下是一个简单的例子。

格式化前：

> 和[[政治虔诚]]的坚定批评而闻名,这些批评中的许多都依赖于心理学诊断.这些诊断揭示了感染人们既有观念的错误意识;出于「这个”原因他经常:与一群晚期现代思想家（包括马克思和弗洛伊德）联系在一起。。。。他们提出了反对传统价值观的“怀疑解释学”。

> 123「45」678

> `![](https://leay.net/text.png)`

> To you, and you alone, 「what matters is the process: the experience of shaping the artwork.」

格式化后：

> 和 [[政治虔诚]] 的坚定批评而闻名，这些批评中的许多都依赖于心理学诊断。这些诊断揭示了感染人们既有观念的错误意识；出于「这个」原因他经常：与一群晚期现代思想家（包括马克思和弗洛伊德）联系在一起……他们提出了反对传统价值观的「怀疑解释学」。

> 123 "45" 678

> `![pic](https://leay.net/text.png)`

> To you, and you alone, "what matters is the process: the experience of shaping the artwork."



## 参考排版规范（包括但不限于）

- [yikeke/zh-style-guide: An open-source style guide for writing Chinese technical documents: https://zh-style-guide.readthedocs.io](https://github.com/yikeke/zh-style-guide/)
- [ruanyf/document-style-guide: 中文技术文档的写作规范](https://github.com/ruanyf/document-style-guide)
- [mzlogin/chinese-copywriting-guidelines: Chinese Copywriting Guidelines：中文文案排版指北（简体中文版）](https://github.com/mzlogin/chinese-copywriting-guidelines)
- 《GBT 15834-2011  标点符号用法》
