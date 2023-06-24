### 界面客服VUE设计

##### 简介

界面客服分为服务端和客户端，两个前端可以交互，用户在客户端输入信息，客服在服务端可以接收用户消息并做出回复。

##### 路由展示（router）

![image-20230523095734477](C:\Users\随行佯醉\AppData\Roaming\Typora\typora-user-images\image-20230523095734477.png)

##### 主体代码结构

![image-20230523095913579](C:\Users\随行佯醉\AppData\Roaming\Typora\typora-user-images\image-20230523095913579.png)

##### 服务端初始界面

```
此时暂时没有用户接入，客服端会话栏显示为空
```

![image-20230523100141548](C:\Users\随行佯醉\AppData\Roaming\Typora\typora-user-images\image-20230523100141548.png)

##### 用户端初始界面

![image-20230523100333882](C:\Users\随行佯醉\AppData\Roaming\Typora\typora-user-images\image-20230523100333882.png)

##### 使用流程

```
此时用户选择转接客服
```

![image-20230523100411453](C:\Users\随行佯醉\AppData\Roaming\Typora\typora-user-images\image-20230523100411453.png)

```
原聊天窗口界面会出现“客服小P为您服务”的提示
```

![image-20230523100520342](C:\Users\随行佯醉\AppData\Roaming\Typora\typora-user-images\image-20230523100520342.png)

```
服务端出现用户接入提醒
```

![image-20230523100630900](C:\Users\随行佯醉\AppData\Roaming\Typora\typora-user-images\image-20230523100630900.png)

```
客服与用户进行交流，客服可以同时发送表情并传输文件
```

![image-20230523100827918](C:\Users\随行佯醉\AppData\Roaming\Typora\typora-user-images\image-20230523100827918.png)

```
用户接收到客服消息，并回复，同时可以发送表情和传输文件
```

![image-20230523100959144](C:\Users\随行佯醉\AppData\Roaming\Typora\typora-user-images\image-20230523100959144.png)

```
若用户在线，客服可以看到用户在线
```

![image-20230523101147329](C:\Users\随行佯醉\AppData\Roaming\Typora\typora-user-images\image-20230523101147329.png)

```
若用户关闭窗口，客服界面显示用户已断开连接（离线）
```

![image-20230523101235074](C:\Users\随行佯醉\AppData\Roaming\Typora\typora-user-images\image-20230523101235074.png)

##### VUE运行后台提示

![image-20230523101034624](C:\Users\随行佯醉\AppData\Roaming\Typora\typora-user-images\image-20230523101034624.png)

##### 代码

相关代码在压缩包里