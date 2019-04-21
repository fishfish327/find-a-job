- 两轮phone interviews：

第一轮：白人大哥
两题，第一题 meeting room2原题， 第二题，给两个string, source and target, 用copy, insert, delete三种操作从source变成target。要求返回操作流程string， 例如copy 'd'就要在返回的string中加Cd, 同理， insert加Ix, delete加Dx. 要求返回的string最短，就是操作次数最少。 经典DP, 不知道有没有更好的方法

第二轮：来自Youtube组的印度小哥
coding：写函数基于index, level，计算杨辉三角的中的对应值。
然后坑壁的东西就来了：
1.如果你跑程序，发现memory占用只增不减，怎么回事？怎么解决？（C++)
2. How processes communicate with each other?
ECE出身，没学过processes的课，不会答，估计挂了

- full time
写Iterator和SkipIterator
Iterator { hasNext; getCurrent; ... }
SkipIterator { hasNext; getCurrent; moveToNext; ... }

实现skip()，比如skip(4)，输入> 1, 3, 4, 1
每次都跳过4，最后返回1
