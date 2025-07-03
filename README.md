# getWebShell
基于java的免杀webshell生成工具
## 免责声明

本程序仅用于学习与研究使用。

## 介绍

本工具可以生成基于tomcat解析器的jsp类型的webshell使用代码层混淆和双重编码混淆绕过防护工具检测，可免杀绝大多数静态查杀和部分动态查杀，目前测试来看有较好的免杀效果。(经测试该工具生成的免杀webshell可适用于tomcat和jetty，其他容器和jsp依赖需进行测试验证)

## 使用方法

python3 getJSP.py（py文件使用前需要安装依赖ebcdic）

或直接使用exe可执行文件

## 其他

目前仅支持哥斯拉webshell的生成后续将持续增加新的webshell类型

jsp多重编码混淆学习可参考以下两位大佬的文章：

https://y4tacker.github.io/2022/11/27/year/2022/11/%E6%B5%85%E8%B0%88JspWebshell%E4%B9%8B%E7%BC%96%E7%A0%81/

https://cloud.tencent.cn/developer/article/2382449

2025.6.23--新增冰蝎3.0默认webshell

2025.6.27--新增冰蝎4.0default_xor传输协议webshell

2025.7.3--新增冰蝎4.0default_xor_base64传输协议webshell
