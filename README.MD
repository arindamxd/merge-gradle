
多组件分包合包的脚本说明：

`fat-aar.gradle`这个脚本经过改动支持`gradle-2.2.3`插件版本以下合并成aar包


`publish.gradle`这个脚本经过改动支持合并aar包之后，整合module中的`远程依赖`成.pom文件，然后发布到nexus私服中，当然了你也可以改造该脚本，让他发布到`jfrog仓库`中去
