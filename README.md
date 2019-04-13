# Hugh's Blog
## 搭建指南
是否安装了git?
```bash
git --version
```
是否安装了node.js?
```bash
node -v
```
## 安装Hexo
```bash
$ npm install hexo-cli -g 
$ hexo init blog
$ cd blog
$ hexo server
```
## 修改站点配置文件
对应的目录 ：blog/_config.yml
```bash
deploy:
  type: git 
  repo: git@github.com:username.github.io.git
  branch: master
```

## 修改网站主题
```bash
$ cd themes
$ git clone https://github.com/iissnan/hexo-theme-next next
```
## 提交仓库
```bash
$ npm install hexo-deployer-git --save
$ hexo g
$ hexo d
```
