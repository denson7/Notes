## 安装
```
$ npm install -D electron
// 查看是否安装成功
$ npx electron -v
v12.0.4
```

### 安装依赖或打包时出现electron包下载过慢问题
修改.npmrc文件
```
registry = https://registry.npm.taobao.org
sass_binary_site = https://npm.taobao.org/mirrors/node-sass/
phantomjs_cdnurl = http://cnpmjs.org/downloads
electron_mirror = https://npm.taobao.org/mirrors/electron/
sqlite3_binary_host_mirror = https://foxgis.oss-cn-shanghai.aliyuncs.com/
profiler_binary_host_mirror = https://npm.taobao.org/mirrors/node-inspector/
chromedriver_cdnurl = https://cdn.npm.taobao.org/dist/chromedriver
```

