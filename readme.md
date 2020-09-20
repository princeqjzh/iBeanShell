环境配置如下：
1. Java 开发环境
2. Maven 运行环境
3. 环境参数： jmeter_path 指向运行的jmeter根目录

运行命令：
mvn clean install 

如果运行正常，做出的jar包会自动部署到 $jmeter_path/lib/ext 目录下