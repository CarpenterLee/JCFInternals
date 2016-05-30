# Java Collections Framework Internals

# Authors

| Name | Weibo Id | Blog | Mail |
|:-----------|:-------------|:-------------|:-----------|
| 李豪 |[@计算所的小鼠标](http://weibo.com/icttinymouse) | [CarpenterLee](http://www.cnblogs.com/CarpenterLee/) | hooleeucas@163.com |

# Introduction

关于*C++标准模板库(Standard Template Library, STL)*的书籍和资料有很多，关于*Java集合框架(Java Collections Framework, JCF)*的资料却很少，甚至很难找到一本专门介绍它的书籍，这给Java学习者们带来不小的麻烦。我深深的不解其中的原因。**虽然JCF设计参考了STL，但其定位不是Java版的STL，而是要实现一个精简紧凑的容器框架**，对STL的介绍自然不能替代对JCF的介绍。

本系列文章主要从**数据结构和算法**层面分析JCF中List, Set, Map, Stack, Queue等典型容器，**结合生动图解和源代码，帮助读者对Java集合框架建立清晰而深入的理解**。本文并不特意介绍Java的语言特性，但会在需要的时候做出简洁的解释。

# Contents

具体内容安排如下：

1. [Overview](https://github.com/CarpenterLee/JCFInternals/blob/master/markdown/1-Overview.md) 对Java Collections Framework，以及Java语言特性做出基本介绍。
2. [ArrayList](https://github.com/CarpenterLee/JCFInternals/blob/master/markdown/2-ArrayList.md) 结合源码对*ArrayList*进行讲解。
3. [LinkedList](https://github.com/CarpenterLee/JCFInternals/blob/master/markdown/3-LinkedList.md) 结合源码对*LinkedList*进行讲解。
4. [Stack and Queue](https://github.com/CarpenterLee/JCFInternals/blob/master/markdown/4-Stack%20and%20Queue.md) 以*AarryDeque*为例讲解*Stack*和*Queue*。
5. [TreeSet and TreeMap](https://github.com/CarpenterLee/JCFInternals/blob/master/markdown/5-TreeSet%20and%20TreeMap.md) 结合源码对*TreeSet*和*TreeMap*进行讲解。
6. [HashSet and HashMap](https://github.com/CarpenterLee/JCFInternals/blob/master/markdown/6-HashSet%20and%20HashMap.md) 结合源码对*HashSet*和*HashMap*进行讲解。
7. [LinkedHashSet and LinkedHashMap](https://github.com/CarpenterLee/JCFInternals/blob/master/markdown/7-LinkedHashSet%20and%20LinkedHashMap.md) 结合源码对*LinkedHashSet*和*LinkedHashMap*进行讲解。
8. [PriorityQueue](https://github.com/CarpenterLee/JCFInternals/blob/master/markdown/8-PriorityQueue.md) 结合源码对*PriorityQueue*进行讲解。
9. [WeakHashMap](https://github.com/CarpenterLee/JCFInternals/blob/master/markdown/9-WeakHashMap.md) 对*WeakHashMap*做出基本介绍。
