#TSDM Minerva
用于天使动漫论坛的数据库索引器，64位版本


----------

 - 配置文件
参见minerva.ini
 - 程序用法
**minerva**
进行完全索引，清除现存的索引
**minerva recent TIME**
进行增量索引，范围为距离现在TIME秒内的主题
**minerva config**
在当前目录生成配置文件模板
 - 附加开关
这些选项可以追加到参数末尾
**nolog**
不输出日志文件
**noredundancy**
不向数据库中写入维持索引非必要的信息
 - 依赖项
libmysql.dll - MySQL 5.7附带的Connector/C，置于相同目录
