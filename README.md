# WIFI-Chat
<h1>基本功能</h1>

1.上线、下线

2.在线列表

3.消息发送

<h1>网络通信</h1>

UDP服务端口	12425（用于监听单播或广播消息，服务端类是DatagramSocket)

UDP服务端口	12426（用于监听组播消息，服务端类是MulticastSocket)

TCP服务端口	12425

<h2>数据包</h2>

数据包内容以 ：隔开 例（协议版本:包序号:发送者用户名:命令字:消息正文）

<h1>数据库表设计</h1>
<h2>消息表</h2>
| 字段           | 数据类型       | 注释  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

<table></table>
