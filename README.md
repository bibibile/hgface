<div align="center">


</div>


* 用于node环境的玩具和容器，基于node三方ws库，集成哪吒探针服务(v0或v1)，可自行添加环境变量

* PaaS 平台设置的环境变量
  | 变量名        | 是否必须 | 默认值 | 备注 |
  | ------------ | ------ | ------ | ------ |
  | UUID         | 否 |5efabea4-f6d4-91fd-b8f0-17e004c89c60| 开启了哪吒v1,请修改UUID|
  | PORT         | 否 |  3000  |  监听端口                    |
  | NEZHA_SERVER | 否 |        |哪吒v1填写形式：nz.abc.com:8008   哪吒v0填写形式：nz.abc.com|
  | NEZHA_PORT   | 否 |        | 哪吒v1没有此变量，v0的agent端口| 
  | NEZHA_KEY    | 否 |        | 哪吒v1的NZ_CLIENT_SECRET或v0的agent端口 |
  | NAME         | 否 |        | 节点名称前缀，例如：Glitch |
  | DOMAIN       | 是 |        | 项目分配的域名或已反代的域名，不包括https://前缀  |
  | SUB_PATH     | 否 |  sub   | 订阅路径   |
  | AUTO_ACCESS  | 否 |  false | 是否开启自动访问保活,false为关闭,true为开启,需同时填写DOMAIN变量 |



    



## 开源协议说明（基于GPL）

本项目遵循 GNU 通用公共许可证（GNU General Public License, 简称 GPL）发布，并附加以下说明：

1. 你可以自由地使用、复制、修改和分发本项目的源代码，前提是你必须保留原作者的信息及本协议内容；
2. 修改后的版本也必须以相同协议开源；
3. **未经原作者明确授权，不得将本项目或其任何部分用于商业用途。**


