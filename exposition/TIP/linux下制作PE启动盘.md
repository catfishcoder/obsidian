1. 下载[WePE.iso](https://subverse-my.sharepoint.com/:u:/g/personal/yanjun_subverse_onmicrosoft_com/ETT2yHK91FxJoi3l9mG1q1MBVoFJXpi7QJtTrc_2IMmlDA?e=eJYn8l)
2. 查看U盘名称：`fdish -l`
3. 取消挂载U盘：`umount /dev/sdb`
4. 格式化U盘：`mkfs.fat /dev/sdb -l`
5. dd系统：`dd if=~/Download/WePE.iso of=/dev/sdb`
6. 最后等待结束