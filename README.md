# weblog
weblog  vauepress

# start 

## install 

初始化
```shell
# npm install -g yarn # if no yarn please install 
yarn init
```
安装 vuepress本地依赖，不推荐全局安装
```shell
yarn add -D vuepress
```

创建文章
```shell
mkdir docs && echo '# Hello Vuepress' > docs/README.md
````

在`packa.json`中添加`scripts`
```json
"scripts": {
    "docs:dev" : "vuepress dev docs",
    "docs:build" : "vuepress build docs"
  }
```

本地启动服务器
```shell
yarn docs:dev
```

nice
