# 1 pipeline概述
![](https://upload-images.jianshu.io/upload_images/4685968-f24a23cb3720de85.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-c019af95d7942261.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
# 2  pipeline初始化
![](https://upload-images.jianshu.io/upload_images/4685968-863545b33707eaa7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-af37cd390d69636f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-87484b188f0d1c8c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-2b7a40da049a9e0b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![双向链表结构](https://upload-images.jianshu.io/upload_images/4685968-f283442b2c53c8e8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-795cae43bcc835cf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-9acb220d5d85971a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-9a8ded204537aba4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
看看其一个实现类
![](https://upload-images.jianshu.io/upload_images/4685968-bfa9f48950727d7a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
基本数据结构组件
![](https://upload-images.jianshu.io/upload_images/4685968-7c511485a10befe6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-8d453a32488036b6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-fe50e58473302307.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-626baf4c8d874a9b.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-b3072070dd46953f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-37d04eb49ef9d178.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-fa173a42edd926da.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
# 3 添加ChannelHandler
先看看用户代码
![](https://upload-images.jianshu.io/upload_images/4685968-ca7da0ba5d56c15a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-00ddba860a27a7ab.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-e50c17a056f3cfde.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-cd4e9f6eab550427.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-e1a563d560be0ace.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-c4b1672f7c23015c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-a69d352e9421fffd.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-4381efb7d3a8e94e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-a0f6849250f0b003.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-f4ebcc820d2d5bbb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-f43bb30c956a1aab.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-1c128b8c51fbe6f8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-f05015c612d4a937.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-6951a2ee0760b306.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-249669a453333360.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-dd50f0772d0ddb91.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-1dcd944d159812d4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-8421b3a0e59babe1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-9020c07f278ebbaf.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-0af23ab4a9379e54.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-a8d8677a4993558c.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![用户方自定义实现即可](https://upload-images.jianshu.io/upload_images/4685968-98a581d42b4e7288.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-440e88fe89d74605.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
# 6 outBound事件的传播
![](https://upload-images.jianshu.io/upload_images/4685968-2cfd135d3979bdef.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-2110e4882dab2338.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-7fadaa9afdc51a0f.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-870d92e54387ddd4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-5045a64bb3b52186.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-90e9b0a9fbe81ac6.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-a1867d7279159a6d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-c0313c1dbfe62fda.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-c901543ae31b1b56.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-564464652771add4.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-72d9ca0bb597c133.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-d270439d4bb5ada9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-29182961dc0f3259.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-49aef6ebd54b3318.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-9cdf84e80b36450e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-0b7e3524249efcbb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-2b922c567e6f951d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-803ca410dffa4621.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
同理以后的过程
![](https://upload-images.jianshu.io/upload_images/4685968-ef3cca5fcbf86e92.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
# 7 异常的传播
![](https://upload-images.jianshu.io/upload_images/4685968-23cc2f3662965dd8.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-9dbbba3e703266da.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-92fbf794f88e0cd7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-100ca8c39e68da7a.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-66747606f9099273.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-576c4b9ec3899a94.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-6dc7f44a36c976d9.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-48626d4a8b357116.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![对应 tail 为当前节点的情形](https://upload-images.jianshu.io/upload_images/4685968-b3a3031f8b73b1e1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-9209c453c1edc928.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
最佳实践
![在最后定义异常处理器,否则默认是 tail 节点的警告打印信息](https://upload-images.jianshu.io/upload_images/4685968-6c290447b86fb4cb.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![所有异常最终处理位置](https://upload-images.jianshu.io/upload_images/4685968-fdb258a02bb51fb7.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
# 8 pipeline总结
![](https://upload-images.jianshu.io/upload_images/4685968-c275e8e8570cc9f1.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
![](https://upload-images.jianshu.io/upload_images/4685968-f1ea4aa2153d4328.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
调用 pipeline 添加节点时,netty 会使用 instanceof 关键字判断当前节点是 inboound 还是 outbound 类型,分别用不同的 boolean 类型变量标识
![](https://upload-images.jianshu.io/upload_images/4685968-1d68fb47c10b1466.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
inbound 事件类型顺序正相关
outbound 逆相关
![](https://upload-images.jianshu.io/upload_images/4685968-e680e747ccf2a7ce.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
异常处理器要么从 head 或者 tail 节点开始传播
inbound事件则从当前节点开始传递到最后节点
outbound事件则从当前节点开始传递 到第一个 outbound节点
