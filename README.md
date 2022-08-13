# FKCI
### 打卡脚本

一基于selenium driver的自动打卡脚本，没想过会要使用如此长的时间。

此脚本非我原创，其它地方也可以搜到，但是我觉得github更好，同时也改了一丢丢东西，原理简单，所以也不加啥license了

使用方法主要是改动那几个账号和密码，都在前面的定义变量里。打卡后会生成一名为 amFked 的文件，如检测到该文件，则不再尝试打卡, 晚上的时候文件会被删掉，如此循环。

### A auto clockin script


A auto clockin script based on selenium, never thought would be used such a long time.

This script is not created by me, and can be found at elsewhere. But I think github is the best. I changed a little from its' original version, easy, anyone can do anything they want, no licsence here.

Useage is mainly about change the account and the pw, all in definition of first dozen lines. After clockin, a file named "amFked" will be created, if the file is detected, script won't try to clockin, the file will be deleted at night, and loop forever.
