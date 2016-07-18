# maven-archetype-multi-modules-gen
A demo defining your maven archetype which has multi-modules, you can use it to build the archetype of project quickly

本DEMO参考《Maven 实战》第18章 archetype 实现！

##　使用操作

1. 安装jar包到本地

> mvn clean install

2. 编写自定义的archetype-catalog.xml的文件，指示maven-archetype-plugin引用的archetype列表文件位置

> mvn archetype:generate -DarchetypeCatalog=${definedSource}
//${definedSource}为archetype-catalog.xml的来源

3. 根据交互式命令输入对应参数，完成项目骨架自动生成
<br/>
关于archetype的详细内容讲解可以参看《Maven实战》第18章内容，或者(鄙人的笔记)[https://www.zybuluo.com/Bern/note/161923]。


