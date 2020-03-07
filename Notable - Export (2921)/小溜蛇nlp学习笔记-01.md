# 小溜蛇nlp学习笔记-01
## 1. Word vectors
### definition
- <font color=#0099ff size=3> word vectors </font> are sometimes called <font color=#0099ff size=3> word embeddings/word representations </font>. They are a <font color=red size=3> distributed </font> representation.
### ideas:
- go through each position t in the text, which has a center word c and context ('outside') words o
- use the <font color=#0099ff size=3> similarity of the word vectors </font> for c and o to <font color=#0099ff size=3> calculate the probability </font> of o given c.

**用outside word预测center word/用center word 预测 outside word**

![](Notable - Export (2921)/attachments/Clipboard_2020-03-07-01-07-05.png)
