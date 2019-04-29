# InnoDB-Restore-tool
InnoDB Restore tool

恢复Mysql数据库InnoDB文件的小工具,百度搜到的，备份下

环境要求：

>.net >4.0
>mysql >5.6.0

用法：

`InnoDBRepair <username> <password> <port> <srcdir> <destDB>`

编译命令：

`csc /r:mysql.data.dll InnoDBRestore.cs`

已知错误：

`ERROR 1030 (HY000): Got error -1 from storage engine`

>换用高版本的mysql进行恢复，推荐使用5.6.24版本。

引用：

>http://dev.mysql.com/downloads/utilities/

>http://dba.stackexchange.com/questions/57120/recover-mysql-database-from-data-folder-without-ibdata1-from-ibd-files
