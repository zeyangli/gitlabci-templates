# GitlabCI templates


- jobs : 作业模板目录
- templates : 流水线模板目录



## 当前功能

- maven/npm打包
- 单元测试
- 代码扫描（多分支、Pullrequest集成）
- 制品上传（artifactory、阿里云镜像仓库）



## 使用方法

- 标准模板： 系统设置 -> CICD -> General pipelines -> Custom CI configuration path

- 个性化： 使用include引入模板文件，进行自定义参数控制。