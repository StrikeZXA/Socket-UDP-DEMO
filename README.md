# 基于Socket UDP协议的单播Demo

- UDPProvider监听接收到的消息后打印发送者的IP地址和端口,然后构建一份回送数据"Receive data with len"，即发送者的数据长度
- UDPSearcher发送"Hello World!"并打印回送者的IP地址和端口