## dp summary

### 总结
```
1. 依赖于子问题的的n个结果. xn 依赖 xn-1, xn-2....
E070(输入为整形), M062(输入两个整形表示二维数组), M091(输入为一个字符串)
2. 依赖于子问题的结果 和 一个变量x. 
E053(输入为数组), E121(输入为数组), M1191(输入为一个数组和一个整形)
3. 依赖于子问题的n个变量 x1,x2...
E746(输入为数组), E198(输入为数组), M523(输入为数组)
4. 存储中间结果。
E303(输入为数组)
```

### 解题步骤
```
part1: 检测特殊输入(有可能没有)。
part2: 初始化变量(递归式使用的变量)。
part3: 实现递归式(循环)。
part4: 返回结果。

```