## NameService

NameService是rocketMQ的注册中心，保存所有Broker、Topic的元数据。Broker启动后会向NameService发送心跳，NameService也会定时检测broker的可用性，并移除不可用的broker。

