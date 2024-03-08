<!--
    需要填充的占位符：
    
    README.md
    
        乌云知识库：文档中文名
        {nameEn}：文档英文名
        {urlEn}：文档原始链接
        wooyun：域名前缀
        飞龙：负责人名称
        wizardforcel：负责人 Github 用户名
        562826179：负责人 QQ
        wooyun-drops：ApacheCN 的 Github 仓库名称
        wooyun-drops：DockerHub 仓库名称
        wooyun-drops：PYPI 包名称
        wooyun-drops：NPM 包名称
    
    CNAME
    
        wooyun：域名前缀

    index.html
    
        乌云知识库：文档中文名
        #333：显示颜色
        wooyun-drops：ApacheCN 的 Github 仓库名称

    asset/docsify-flygon-footer.js
    
        wooyun-drops：ApacheCN 的 Github 仓库名称
-->

# 乌云知识库

> 协议：[CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/)
> 
> 真相一旦入眼，你就再也无法视而不见。——《黑客帝国》

* [在线阅读](https://wooyun.flygon.net)

## 下载

### Docker

```
docker pull apachecn0/wooyun-drops
docker run -tid -p <port>:80 apachecn0/wooyun-drops
# 访问 http://localhost:{port} 查看文档
```

### NPM

```
npm install -g wooyun-drops
wooyun-drops <port>
# 访问 http://localhost:{port} 查看文档
```
