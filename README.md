## Rafter
在一些不是强一致的系统要转换为强一致的系统时候，就需要进行大量的改造，那么如果有一个CP壳，直接对接下是不是就可以快速的将一个系统进行直接CP改造了呢，于是就想到了raft算法，于是就打算实现一个raft的壳，然后不同的系统直接使用该壳（或者说叫客户端吧），然后就直接变成cp系统了

## 快速入门

### 客户端使用

