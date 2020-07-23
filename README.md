# install 
```
npm install -g pm2cmd
```

# usage 
```
  pm2cmd 查看所有命令

  pm2cd  <pm2_id>  cd到项目目录
  
  pm2reload <pm2_id> 重启并查看标准输出日志

  pm2up <pm2_id> 在项目目录执行svn up

  pm2out <pm2_id> vim查看out日志文件

  pm2error <pm2_id> vim查看error日志文件

  pm2log <pm2_id> <date_pattern> 查看某项目的压缩日志内容件

  pm2port 列出pm2启动的node程序都监听了哪些端口

  pm2l [name_pattern] 根据appName模糊查询pm2列表

  pm2id [num] 获取最后num次使用的pm2命令(最后包含pm2_id的命令)

  pm2save [pm2_home_dir]  保存当前pm2进程

  pm2restore [pm2_home_dir]  恢复pm2进程
```
