# hhys
hhys是一个正在用java编写的开源的分布式服务，作者正在努力搬砖中，所以初期更新速度较慢，预计实习结束后会大幅度更新至第一次迭代结束。<br/>
那么问题来了，这个框架有什么特点？（以下说的特点都会实现，但是目前没时间，预计十月份吧）<br/>
1.可选通信方式，底层基于netty和httpClient，根据业务场景不同选择不同的方式。<br/>
2.跨语言支持，第一次迭代只会支持java，后续会接入其他语言。<br/>
3.服务与注册中心使用zookeeper，暂时没想过支持别的。<br/>
4.实现自己的classloader，不对原有程序侵入太多，支持开源的插件化开发（这个要十月末）。<br/>
5.性能不一定会很好，毕竟作者能力有限，会不断优化。<br/>
6.优化日志系统，支持MQ分发日志，使日志寻找更加方便，为日后添加日志可视化以及全链路追踪做准备<br/>
7.注解即可用原则，极大简化开发流程。<br/>
8.软负载均衡算法，这个就不用说了
