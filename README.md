原 仓库地址：https://github.com/yeayee/joyful-pandas，
我个人从这里学习测试，并加入一些个人理解

#### 大纲

本项目共有十章，可以大致分为4个板块：Pandas基础、四类操作、四类数据、例子。

1、拿到数据必然先要读取它，分析完了数据必然是要保存它，读取了数据之后，我们面对了怎样的对象（Series? or Dataframe?）是第一重要的课题，因此了解序列和数据框的常规操作及其组件（component）便是必须涉及的内容。

2、对于一个DataFrame而言，如果一个操作使得它的元素信息减少了，那就对应了索引，即第二章的内容；如果这个操作使得数据的信息被充分地使用，那有两种可能，第一是数据被分组，从组内提取了关键的信息，第二就是数据呈现的结构或形态上的变化，使得我们更容易地能够地进一步处理数据，这两者分别对应了第三章与第四章的内容；最终如果一个操作使得原本不属于这个数据框的信息被加入了进来，那往往是涉及到了合并操作，对应了第五章的内容。从数据信息增减的角度，拆解成了3个板块，4个章节，几乎串联其了官方文档关于数据框操作的全部内容，我想这样的安排是合适的。

3、如果说前面我们关心了序列和数据框这两种容器的结构和操作，那么下面就要关心其中的元素。其中，将涉及四类特殊的数据类型：缺失型数据、文本型数据、分类型数据和时间序列型数据，分别对应了6-9章的内容，并且在缺失型数据和文本型数据中，将详细涉及Pandas1.0版本新的Nullable和string数据类型，这也是从上一个版本0.25.3升级后具有最大改动的方面。

4、正如前面所说，Pandas的学习往往是任务驱动型，一个操作或者某个方法，不去使用自然会很快地忘记（除非你天赋异禀！），因此我前九章都会添加“问题和练习”的部分。其中，问题中出现的往往是对于教程中某个细节的深入与补充，或者是关于这一章函数方法的实践理解，希望你能够查阅相关资料阅读以解决问题；而练习部分包含了两个综合题（两个的不同案例），相当于对前面所学的综合运用，虽不是非常复杂，但是想要全完成，还是需要花一些功夫。最终，在第10章中会添加若干难度不一的综合问题（不定期更新）。

基于完整性，我为所有的练习写了参考答案，当然它不一定是优秀的解析，但是不失为一种提示与策略。

最后，祝你有所收获！


#### 参考资料

1、[Python for Data Analysis](<http://93.174.95.29/_ads/A3AD6E6B2504B95EC39A6C57D465BA5D>) Wes McKinney著

2、[Pandas Cookbook](<http://93.174.95.29/_ads/23950B4446ABB5DD27168D6B0FB2C8DB>) Theodore Petrou著

3、[User Guide](<https://pandas.pydata.org/docs/user_guide/index.html#user-guide>) Pandas开发团队编写
