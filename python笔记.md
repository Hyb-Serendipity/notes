
字符串常用操作方法

| 函数 | 含义 | 说明 |
| :--- | :--- | :--- |
| 查找类 |  |  |
| 字符串.find\(子串,开始位置下标,结束为止下标\) | 查询子串是否在字符串中 | 查无结果时返回 -1 |
| 字符串.index\(\) | 同上 | 查无结果时会报错 |
| 字符串.count | 返回子串在字符串中出现的次数 | 有几次返回几,大于等于 0 |
| 字符串.rfind\('子串'\) | 从又右始查找 | 下标还是从左开始数 |
| 字符串.rindex\('子串'\) | 同上 | 同上 |
| 替换类 |  |  |
| 字符串.replace\(旧子串,新子串,替换次数\) | 替换字符串 | 不写替换次数则替换全部 |
| 字符串.split\(分割字符,num\) | 以分隔字符分割整个字符串 |  |
| 连接用的字符串.join\(多字符串序列\) | 合并列表中的字符串数据 |  |
| 大小写转换 |  |  |
| 字符串.capitalize\(\) | 字符串的第一个字转大写 |  |
| 字符串.title\(\) | 每个单词的首字母大写 |  |
| 字符串.lower\(\) | 全部转小写 |  |
| 字符串.upper\(\) | 全部转大写 |  |
| 删除 |  |  |
| 字符串.lstrip\(\) | 删除左侧空白字符 |  |
| 字符串.rstrip\(\) | 删除右侧空白字符 |  |
| 字符串.strip\(\) | 删除两侧空白字符 |  |
| 对齐 |  |  |
| 字符串.ljust\(长度,填充字符\) | 字符串长度小于长度时以填充字符补齐,未填填充字符时使用空格 |  |
| 字符串.rjust\(长度,填充字符\) | 同上 |  |
| 字符串.center\(长度,填充字符\) | 同上 |  |
| 判断 True/False,为空都是 False |  |  |
| 字符串.startswith\(子串,开始位置下标,结束位置下标\) | 检测指定位置是否以子串开始 |  |
| 字符串.endswith\(子串,开始位置下标,结束位置下标\) | 检测指定位置是否以子串结束 |  |
| 字符串.isalpha\(\) | 是否全字母 | 有空格也会返回 False |
| 字符串.isdigit\(\) | 是否全数字 | 同上 |
| 字符串.isalnum\(\) | 是否至少有一个字符且所有字符都是数字或字母 | 同上 |
| 字符串.isspace\(\) | 是否全空格 |  |

运算符中 and 优先于 or
TEST

选取内容后 ctrl + / 批量注释