### 什么是protobuf
可以这么理解，一种数据结构，由google 团队开发；


### 难点
本来我想做的，但是后面发现数据结构太难搞定了；因为这个是按照内容生成的数据；所以有的时候数据结构不一定是固定的；
我想要的是什么，是我拿到一个json之后可以直接转为可以传输的buf；
突然灵机一动，其实我可以将其改为json string，然后我再encode为buf；进行传输之后再uncode到json，

但是问题是传输的过程会不会变快这是个问题；

### 版本
Protobuf.js 4.x的API 和 Protobuf.js 6.x还不太一样


### 参考文档
1. http://imweb.io/topic/570130a306f2400432c1396c
2. https://ivweb.io/topic/59759fbc97baaa5723b4df69
