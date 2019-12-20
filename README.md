# UniqueIDUtil

Twitter [snowflake](https://github.com/twitter-archive/snowflake) 算法的 Java 实现。

# How to use

```java
UniqueIDUtil.getInstance().nextId();
```
or
```java
UniqueIDUtil.getInstance(3, 4).nextId();
```
