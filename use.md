# Introduction #

如何使用iptux(简体中文版)？

# Details #

  * 探测好友，**文件**-->**探测**，向特定的IP发送探测数据包，如果对方在线且向iptux返回了一个数据包，iptux将会在好友列表中添加此好友；
  * 搜索好友，**文件**-->**查找**，从列表中筛选匹配输入字符串的好友；
  * 传输管理，**工具**-->**传输管理器**，可以在此查看正在传输的数据进度或已经完成的传输任务，使用右键菜单可以控制传输工作的运行；
  * 软件设置，**工具**-->**首选项**，对软件进行基本设置：
    * 个人：
      * 您的昵称、您的组名、您的头像，...；
      * 保存文件到，文件的默认保存位置；
      * 个人形象、个性签名，...。
    * 系统：
      * 候选网络编码、首选网络编码，如果软件接收到一个没有标明编码的数据包，软件将优先考察此数据编码是否匹配首选网络编码，如果不匹配，就再考察候选网络编码中是否有匹配数据包的；另，软件的默认输出编码也将无条件采用首选网络编码；
      * 好友默认头像，如果不能获取到好友的头像，就使用此默认头像；
      * 面板字体，设置列表好友的显示字体；
      * 程序启动后自动隐藏面板，...；
      * 自动打开文件传输管理器，当有文件传输时，文件传输管理器被自动弹出；
      * 使用Enter键发送消息，...；
      * 自动清空聊天历史记录，...；
      * 保存聊天历史，...；
      * 开启黑名单处理方案，只要iptux还没有被重启，被删除的好友就不能上线；
      * 过滤好友对共享文件的请求，好友请求获得您的共享文件时，将需要得到您的允许。
    * 声音:
      * 启动声音支持，...；
      * 音量控制，...；
      * 声音事件，可以选择允许那些事件发生时提示声音，以及播放什么声音文件。
    * 网络：
      * 对IP网段的添加或删除处理，iptux在刷新或启动时会对这些网段进行扫描；
      * 导入，导入一个ip网段描述文件中的数据到列表；
      * 导出，导出列表中的数据到ip网段描述文件。
  * 共享管理，**工具**-->**共享管理器**,对共享文件的管理，被设置成共享的文件可以被好友请求获得，而不需要你手工发送；
  * 刷新，**工具**-->**刷新**，刷新好友列表。


  * 获取好友的共享文件
  * 发送文件或文件夹
  * 删除好友


  * 如何使用拖拽操作？将欲发送的文件(允许多个)拖到\*好友图标\*或\*好友对话框\*上，释放，看看会发生什么？
  * 好友编码探测出错，咋办？在\*好友图标\*上点击\*右键**，选择\*更改信息**，在弹出的对话框中设置正确的编码吧(当然也可以将正确的编码改成错误的)！


  * 应该还有一些小功能没有介绍，不过它们的用处不大，可以自己慢慢摸索！