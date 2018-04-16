# MyBaties

## 使用
### 使用方式
#### 编程式
#### 集成式

### 使用过程
分析业务->定义结构->generator生成类
#### 用到的类
|类名|使用域|
| --- | --- |
|SqlSessionFactoryBuilder|method(用一次就完成)|
|SelSessionFactory|application(全局唯一)|
|SqlSession|request/method(线程级别)|
|Mapper|method|

#### TypeHandler:
做数值映射

#### Plugins


## 课后作业
1. Mapper在Spring管理下其实是单例，为什么可以是一个单例？SCOPE -> Application
2. MyBatis在Spring集成下没有mapper的xml文件会不会报错，为什么？
3. 手写TypeHandler


