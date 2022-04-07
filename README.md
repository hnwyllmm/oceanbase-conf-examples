# oceanbase-conf-examples
存放一些用于测试oceanbase的配置文件示例。


oblocal.yaml  测试单机版单节点observer
obdist_with_proxy.yaml  单机上部署两个observer节点，两个zone，1:1模式，带obproxy
obdist-noproxy.yaml  单机上部署两个observer节点，两个zone，1:1模式，不带OBProxy
obdist.yaml  四台机器部署observer，两个zone，2:2模式，不带OBProxy

注意：OBD在同一台机器部署多个observer节点时，不能使用autodeploy方式，只能使用deploy命令。
