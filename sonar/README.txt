Sonar 是一个用于代码质量管理的开放平台。通过插件机制，Sonar 可以集成不同的测试工具，代码分析工具，以及持续集成工具。

与持续集成工具（例如 Hudson/Jenkins 等）不同，Sonar 并不是简单地把不同的代码检查工具结果（例如 FindBugs，PMD 等）直接显示在 Web 页面上，而是通过不同的插件对这些结果进行再加工处理，通过量化的方式度量代码质量的变化，从而可以方便地对不同规模和种类的工程进行代码质量管理。

在对其他工具的支持方面，Sonar 不仅提供了对 IDE 的支持，可以在 Eclipse 和 IntelliJ IDEA 这些工具里联机查看结果；同时 Sonar 还对大量的持续集成工具提供了接口支持，可以很方便地在持续集成中使用 Sonar。

此外，Sonar 的插件还可以对 Java 以外的其他编程语言提供支持，对国际化以及报告文档化也有良好的支持。


注意：soanrqube是一个web界面，scanner才是扫描代码的那个工具。通过它，将项目的代码读取并发送至sonarqube服务器中，才能让sonarqube进行代码分析



Sonar6.0应用之二Sonar Web界面配置及与Runner、Scanner集成进行命令行代码分析
http://www.bubuko.com/infodetail-1802567.html


使用sonar进行代码质量管理
https://www.ibm.com/developerworks/cn/java/j-lo-sonar/


 sonarQube之sonarLint扫描
http://blog.csdn.net/songer_xing/article/details/76691148


 sonarQube之jenkins可持续化集成
http://blog.csdn.net/songer_xing/article/details/76691438


sonarqube代码质量管理平台环境搭建及实践（一）
https://www.jianshu.com/p/f11fbd1c316e


使用 Jenkins 与 Sonar 集成对代码进行持续检测
https://www.ibm.com/developerworks/cn/devops/1612_qusm_jenkins/index.html



soanrqube软件包下载
https://www.sonarqube.org/downloads/



sonar中文软件包
http://repo1.maven.org/maven2/org/codehaus/sonar-plugins/l10n/sonar-l10n-zh-plugin/