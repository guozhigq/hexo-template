# hexo-template

hexo blog templete
<https://hexo.io/zh-cn/>

# start

-   npm install hexo-cli -g
-   git clone <https://github.com/guozhigq/hexo-template>
-   cd hexo-template
-   npm install
-   hexo server

## 部署到 Github

1. 安装 hexo-deployer-git 插件
   cd hexo-template & npm install hexo-deployer-git --save

2. 编辑根目录下\_config.yaml 文件，修改结尾内容

```js
deploy:
  type: git
  repo: github上对应仓库的ssh 链接
    //也可使用https地址，如：https://github.com/Github用户名/Github用户名.github.io.git
  branch: main
```

3. 将本地仓库推送到远程

-   输入命令: hexo d
