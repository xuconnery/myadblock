# myadblock

此项目是自用的网页广告屏蔽规则。

项目地址: https://github.com/xuconnery/my_adblock

# 说明

"!"符号标记的规则不生效，为注释。

"||" 为子域通配符 方便匹配主域名下的所有子域。比如 "||www.baidu.com" 就可以不要前面的协议"http://"。

"^" 为分隔符 可以匹配任何单个字符。

"|" 为管线符号 来表示地址的最前端或最末端 比如 "|http://" 或 |http://www.abc.com/a.js| ，用于精确控制匹配的开始或结束。

订阅地址: https://raw.githubusercontent.com/xuconnery/myadblock/master/adblock.txt

# update

- 2020-1-13 创建规则
