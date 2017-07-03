# Python 作业 8

下载附件0008.zip（见附件[0008.zip](https://raw.githubusercontent.com/jcyrss/songqin-testdev/master/python/task/attachs/0008.zip)）

```python


解压该压缩包，里面 包含了3个文件。 都是数据库中导出的数据文件，
记录了松勤的老师和授课信息。

其中

1. teacher.txt 文件中包含了 松勤的老师信息，格式如下：

id;user_id;desc;display_idx;realname
42;106;;1;小猪老师
43;107;;2;mandy老师

首行表示 下面数据各字段的含义。 
第1列id 表示老师的id号。
第2、3、4 列的含义大家可以先不必了解。 
第5列realname 表示 老师的姓名


2. course.txt 文件中包含了 松勤的课程信息，格式如下：

id;name;desc;display_idx
32;软件测试框架课程;;1
33;web测试技术课程;;2

首行表示 下面数据各字段的含义。 
第1列id 表示课程的id号
第2列name 表示 课程的名称
第3、4 列的含义大家可以先不必了解。 



3. teacher_course.txt 文件中包含了 松勤老师授课信息，格式如下：

teacher_id;course_id
42;32
42;33

首行表示 下面数据各字段的含义
第1列teacher_id 表示老师的id号（对应第一张表的老师id号）
第2列course_id表示 课程的id号（对应第二张表的课程id号）。




要求大家编写一个python程序，根据这3张表的内容，输出一个包含老师授课信息的文件。
要求格式为 老师姓名: 课程名，例如

小猪老师    :  软件测试框架课程
mandy老师   :  软件测试框架课程
mandy老师   :  web测试技术课程


实现过程中，有什么问题，请通过课堂上讲解的调试方法，尽量自己发现错误原因。


```





## 参考答案，往下翻
<br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br><br>

```python

```