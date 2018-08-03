**python 库结构**
---
package folder -+
                |
                +setup.py          <--主要的配置/安装文件，**必须**
                |
                +setup.cfg         <--提供给用户的配置文件，可选
                |
                +README            <--readme 文件，可选
                |
                +MANIFEST.in       <--打包配置文件模板，用来和setup.py一起生成打包配置文件MANIFEST，可选
                |
                +<your package>    <--你的package，最好与package folder名字一致
                |
                +<other files>     <--额外的文件