#### 编译步骤



###### 克隆代码

```shell
git clone https://github.com/Tesla-AC/filebrowser.git
```

###### 构建前端

```shell
cd frontend
# 安装依赖
npm install
# 构建
npm run build
```

###### 构建后端

```shell
# 安装依赖
go mod download
# 构建无控制台程序
go build -ldflags="-s -w -H=windowsgui"
```



直接运行exe文件即可
