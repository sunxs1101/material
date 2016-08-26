在Python中使用JSON超级简单，JSON和Python的字典很像，可以转换。看官方文档即可

 - json库 https://docs.python.org/2/library/json.html

掌握下面这些库会让你处理json和字典的时候更开心

 - attrdict https://github.com/bcj/AttrDict a['foo']['bar']可以写做a.foo.bar 或a['foo'].bar。可读/写属性，可递归访问属性，继承dict的各种方法
 - marisa-trie https://github.com/kmike/marisa-trie 超级节约内存的字典
 - DAWG http://dawg.readthedocs.org/en/latest/ 另一个超级节约内存的字典
 - orderedmultidict https://github.com/gruns/orderedmultidict 多值有序字典
 - jsonpickle http://jsonpickle.github.io/ JSON持久化。支持更复杂数据的存储
 - jq http://stedolan.github.io/jq/tutorial/ 命令行上的json处理和查询
 - pjson https://github.com/igorgue/pjson 在命令行上彩色打印json
 - jsonlint https://github.com/zaach/jsonlint 格式化json
 - jsawk https://github.com/micha/jsawk json的awk，一个快速的命令上的查询工具
 - json-diff https://www.npmjs.org/package/json-diff 比较两个json

以上都是良心推荐，多年工程实战考研的趁手工具。掌握了这些即使学不好知识图谱，也可以成为不错的数据科学家 :D

还有一些高级的话题，json pointer， json schema， xml2json， csv2json，暂时不提。我们只需要知道，json的工具链极为丰富。很多时候我们处理数据，就是卡在这些“小”工具上。你要是用了RDF，就会在无数小地方上因为缺少这些小工具而痛苦。

最有要隆重推荐一下YAML：JSON的超集，有更简洁的语法 http://yaml.org/
YAML在我看来比JSON的可读性更好，更加Pythonic（因为其语法接近Python）。当然有人可能会不喜欢缩进，不过Python社区的智力一般比较高，不会有这种偏见。YAML里可以有节点之间的链接，因此可以表示图。此外yaml里可以写!注!释！我认为YAML是天然的最好的知识图谱表示语法。

PyYAML是Python里的Yaml处理库 http://pyyaml.org/wiki/PyYAML
不过Yaml解析的速度比json慢得多，大概只有1/10。但是我们要牢记，知识表示最重要的是对人的友好，不是对机器的友好。速度不是大的问题，大部分的知识库都不是特别大。
最后多说一句无关的话，很多语言都有可读性更好的类Python语法。下面是我收集的一个列表

有一本经典的编程书《The Art of Readable Code》 https://book.douban.com/subject/5442971/ 。我觉得同样的在知识表示里，我们应该追求“易读知识的艺术”。工程上，这是特别重要的一件事。
