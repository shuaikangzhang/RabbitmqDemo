### 本例：
    轮询模式，每个消费者接受到相同数量的消息

#### 前提：
    生产者发送50条消息，消费者1需要两秒处理数据，消费者2需要一秒处理数据，
#### 测试结果：
    两个消费者接受到的数据数量是一样的，都是25条
