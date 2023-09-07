
# workshop guide


## 实验目标
1. 开发者在JFrog Artifactory配置仓库进行构建。
2. 开发者进行maven构建，通过Artifactory进行依赖下载。
3. 开发者将构建包上传到Artifactory，并进行漏洞扫描。
4. 开发者将构建的jar包放入docker镜像并构建镜像。
5. 扫描docker镜像，配置漏洞扫描策略，阻止超高危漏洞的下载。
        
## 准备
1. 获取Artifactory 账号 

username/password = Labuser1/xxxxxx, Labuser2/xxxxxx ...
以上由现场工作人员提供。 

浏览器访问：http://demo.jfrogchina.com，进行登录。
2. 获取实验代码
```shell
git clone git@github.com:alexwang66/eplus-training.git
```

## 实验 1 - maven build & scan demo

                