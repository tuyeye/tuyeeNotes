# tuyee 的备忘录 📕
🏆 记录（备份）一些开发过程中觉得比较重要的语法或者注意点，如果发现更好的用法或者发现了错误，会在原处下方贴出新的解决方案，学习的过程嘤嘤嘤～

### git 提交本地分支到远程仓库
```bash
$ git push origin HEAD -u 
```

### linux 系统安装 redis 后，查看 redis 记录
```bash
$ redis-cli -h 127.0.0.1 -p [端口号]
$ auth [密码]
$ key *
```

### centOs 搭梯子脚本
```bash
$ wget -N --no-check-certificate https://raw.githubusercontent.com/ToyoDAdoubiBackup/doubi/master/ssr.sh && chmod +x ssr.sh && bash ssr.sh
```

### netcore 实体类生成脚本（Mysql版）
```bash
$ dotnet ef dbcontext scaffold [数据库连接字符串] Pomelo.EntityFrameworkCore.MySql --output-dir Models --namespace [命名空间]
```
> 数据库连接字符串要加上 Allow User Variables=True 原因为啥搞忘了


