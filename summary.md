# RabbitMQ的使用
## 一些概念

Message：

    消息头 + 消息体
    消息头：
        routing key：路由键
        priority：相对于其他消息的优先权
        delivery-mode：指出该消息可能需要持久性存储
    
    Publisher：消息生产者，也是一个向交换器发布消息的客户端应用程序 
    Exchange：交换器，用来接收生产者发送的消息并将这些消息路由给服务器中的队列
        direct：
        fanout：
        topic：
        headers：
        
# 消息模式

## 简单模式
## Work Queue
    1、一条消息只有一个消费者
    2、轮询
    3、消费者在处理完某条消息后，才会收到下一条消息
    
    
                