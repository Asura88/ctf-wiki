# DoS

对内核进行 DoS 攻击比较容易，我们可以通过以下几种方式来实现。

- 触发内核中的某个漏洞让内核崩溃
- 触发内核中的死锁
- 触发大量的内核内存泄漏，即存在大量的内存被申请但是没有被释放