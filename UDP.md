[TOC]

#### QT的UDP协议
- 不需要连接
- 传输快,带宽小,实时性强
- 对安全性要求不高,对实时性要求高

###### 通讯方式
- 单播通讯(点对点)
- 组播通讯(多播)
- 广播通讯

###### QUDPSocket类
- 发送方:创建套接字,发送数据
	- 创建套接字
	- 发送数据(writeDatagram)
- 接收方:创建套接字,绑定,接收/发送数据
	- 创建QUDPSOcket对象
	- 绑定(bind)
	- 接受数据(readDatagram)
