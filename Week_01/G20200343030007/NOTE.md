## 学习笔记

### 数据结构与算法理解

计算机程序语言都是重复，究极就是重复的，是有规律的，所以所有的算法是可以找规律，套模板的。

### 如何学习

- **刻意练习**

  就像打游戏一样，补兵不行一直练补兵，技能不行一直练技能，大神都是每一步基础都很扎实，所以基本功是制胜法宝。

- **刷题**

  1. 敢于承认自己刷题时，***想不出来，不会做*** 的问题，因为优秀的算法时前人总结多年的经验，我们不是圣人，我们只是学习者，记下优秀的思路技巧，并做到熟能生巧时最重要的。
  2. 刷题只做一遍是不可以的，以为看会了，照着写出来了就等于会了，**大错特错**！这是基本功，是需要达到见到这个题就可以立马想到解法，并且迅速写出来，达到这样的境界，只做一遍是万万不可的。
     - 第一遍：思路看懂，程序做熟
     - 第二遍：第二天重复默写，加强记忆
     - 第三遍：周天再写一遍，加强记忆
     - 第四遍：第二周写一遍
     - 第五遍：面试前突击练习

- **总结**

  人脑记不住琐碎的知识，但可以归纳总结为脑图，**树**的形式

  将学习的算法和数据结构知识总结为脑图，并在阶段性学习完毕后，看一下自己的算法数据机构地图添加了哪些树枝，还有哪些知识点没有添加。

- **工欲善其事必先利其器**

  - 优秀的 IDE 和插件

    - 可以使用 vscode top tips 这种关键词查询

  - 基本的代码规范

    - 缩行，关键词后跟空格等

    - **自顶向下的编写方法**

      先写大体主干，再写细节方法。

      比如计算盛水最大面积的题目，先 getMinHeight (求最小高度)，再 getArea（求面积），最后 getMaxArea（求最大面积)。先写出大概框架思路，再补足方法细节。这样就不会套进纠结方法细节的误区，导致整个算法没有实现。

  - 代码编写时的指法

    - 快速到达行头行尾
    - 以单词为单位左右移动
    - 向上向下移动当前行代码
    - 整段删除或复制

### 本周刷题总结

- **思路**

  - 基本思路

    如果做不出来，可以尝试大脑中最基本的解法，一步一步程序执行的那种，或者暴力解法 for 循环这种。

  - 其它思路

    本周影响最深刻的是对于双指针的理解，精妙

    - 快慢指针法
      - 移动零
    - 双指针紧逼法
      - 计算最大盛水面积

    **真的是有套路可言！**