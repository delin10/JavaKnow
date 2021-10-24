![Disruptor-整体架构](./images/Disruptor-整体架构.png)

Sequence：CAS实现的原子序列生成器，解决了伪共享的问题；

EventProcessor：队列的消费者处理器，分为批量处理器和顺序处理器；

Sequencer：序列生成控制器，分为单生产者和多生产者两种场景下的实现；

EventFactory：用于创建数据容器，是环形队列中的元素；



- [ ] Log4j2
- [ ] Kafka

