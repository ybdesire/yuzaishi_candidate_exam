羽在石公司“NLP研发”实习生笔试题
-------


# 1. 题目要求

1. 题目仅供羽在石公司实习生上机考试
2. 答题时间为收到题目开始的48小时之内，超过48小时不提交结果的视为放弃
3. 开放性答题，可以自由上网查找资料。不懂的内容自行学习，自学能力也是考题的一部分
4. 代码要求：用python3写程序，要写main函数，程序保存为.py文件，需要有良好的编码规范（参考PEP8的要求：https://www.python.org/dev/peps/pep-0008/）
5. 注释与git commit要求用英文写
6. 关于羽在石公司，可以查看官网了解更多细节：http://www.njainet.com/


# 2. 题目1：中文NER（命名实体识别），总分65分

（1）给定数据集
 * 数据：https://github.com/xuanzebi/BERT-CH-NER/blob/master/tmp/dev.txt
 * 标签：https://github.com/xuanzebi/BERT-CH-NER/blob/master/tmp/dev-lable.txt

（2）自行学习NER（命名实体识别），并用给定的数据，训练一个NER模型，在测试集上判断识别率

（3）不能使用数据集中给定的这个模型：https://github.com/xuanzebi/BERT-CH-NER/，不能使用百度/阿里等需要网络连接的API。

（4）可以自行查找，借助其他开源项目来完成。完成任务即可，对使用的技术没有限制，但必须使用离线SDK/技术来完成。下面给出一个参考，可以直接根据它的描述，把数据适配后得到结果，也可以自己找其他的参考来完成。

* https://github.com/Determined22/zh-NER-TF

（5）及时把自己写的代码push到自己的github，能完成多少就做多少，最终根据完成的内容进行打分。在readme里写清楚：思路，借助了哪些工具/开源项目，自己完成的代码，潜在的问题，将来如何提高/优化


# 3. 题目2：中文OCR，总分35分

（1）对下图中的文字进行识别，并将结果保存为格式化json文本

* https://github.com/ybdesire/yuzaishi_candidate_exam/blob/master/table-pic-for-ocr.png
* 如果打不开，及时微信联系公司负责人

（2）及时把自己写的代码push到自己的github，能完成多少就做多少，最终根据完成的内容进行打分。在readme里写清楚：思路，借助了哪些工具/开源项目，自己完成的代码，潜在的问题，将来如何提高/优化

（3）可以自行查找，借助其他开源项目来完成。完成任务即可，对使用的技术没有限制。这里也给一个参考：

* https://github.com/myhub/tr


