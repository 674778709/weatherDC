### 气象数据处理中心

气象数据中心整体流程：
1、利用“中国气象站点参数.ini”中的所有气象站点信息，每隔一分钟生成一个对应的气象信息
2、生成的气象数据信息保存在单独的文件中
3、将气象数据信息通过FTP传送到数据中心
4、数据中心将传输过来的信息保存到ORACLE数据库中
5、前段APP可以调用相关的接口从ORACLE数据库中读取数据并展示
