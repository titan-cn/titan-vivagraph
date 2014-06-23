该项目是Titan前端可视化的展现，包括前端在线更新graph的一些操作(插入顶点vertice、删除顶点vertice、插入边edge)，实际上调用的是rexster server提供的REST API，关于更多的API可以参考这里：https://github.com/tinkerpop/rexster/wiki/Basic-REST-API

显示的数据就是[Titan-wiki](https://github.com/thinkaurelius/titan/wiki/Getting-Started)官方提供的一个GOD数据类[GraphOfTheGodsFactory.java](https://github.com/thinkaurelius/titan/blob/master/titan-core/src/main/java/com/thinkaurelius/titan/example/GraphOfTheGodsFactory.java)。

graph的可视化展现使用的是这个库：[VivaGraphJS](https://github.com/anvaka/VivaGraphJS)

关于Titan的搭建和配置可以参考这篇文章：http://findhy.com/blog/2014/06/19/titan-tutorial/

运行index.html之前，请修改url中的rexster-host-ip为你的具体地址  

    var url = "http://rexster-host-ip:8182/graphs/graph"