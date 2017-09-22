windows下安装redis：
下载redis的zip包（https://github.com/MicrosoftArchive/redis/releases）；
解压
打开cmd界面
找到zip解压后的文件位置（cd ...redis.xx）
输入 redis-server  redis.windows.conf  启动redis服务
出现一个正方体图形，启动成功。（不成功请自行网上搜索）
不要关闭cmd（关闭redis服务也关闭了），再重新打开一个cmd界面：
找到redis文件位置，输入：redis-cli.exe -h 127.0.0.1 -p 6379 启动一个客户端（注意修改自己的IP！）。
输入 set name Tom 回车
再输入 get name 回车
得到 Tom
