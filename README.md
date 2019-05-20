# publog
简单的博客发布部署项目
技术选型: 
1. Electron 主体
2. mdEditor -> 编辑器
3. ejs -> 模板引擎
4. sqlite3 -> 数据存储
5. simple-git -> git保存操作
6. ftp-deploy -> ftp保存操作
7. sftp-sync-deploy -> sftp 保存操作
8. express -> 本地服务
9. pinyin -> 中文转拼音，生成文件夹及路径使用
10. bootstrap -> 界面布局

## 开发项目开发

```
# 拉取代码
git clone https://github.com/xiaqiubo/publog.git

cd publog 
# 安装依赖
npm install
# 启动本地服务开发
npm run dev
```

## 项目打包
```
# 拉取代码
git clone https://github.com/xiaqiubo/publog.git

cd publog 
# 安装依赖
npm install
# 打包
npm run build
```

## 项目Todos

- [ ] bootstrap / meditor 界面布局 
- [ ] sqliet3 数据表及关系创建
- [ ] 项目按路径生成
- [ ] 发布部署
