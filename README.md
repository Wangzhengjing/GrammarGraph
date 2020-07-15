# GrammarGraph
语法规则图形化

# 用法说明
## 命令使用说明
`./transform grammar.txt`生成`dig.dot`文件；
(预先安装软件`graphviz`)执行命令`dot -Tpng dig.dot -o dig.png`，生成`png`格式图片；
打开图片`dig.png`即可预览；

## 使用相关技巧说明
### 如何查看某个语法规则的关系图
执行命令`cat grammar.txt | grep "<var ref>" > varref.txt`，生成对应语法关系文本；
按照《命令使用说明》中的步骤，生成对应`png`图片文件即可。
