# 初始数组

如何写一个程序计算用户输入的数字的平均数，并输出所有大于平均数的数？

**关键问题：**如何记录很多数？

## 知识点

1. 定义数组

```c
int number[100];
```

2. 对数组中的元素复制

```
number[cnt]=x;
```



3. 使用数组中的元素

```
if(number[i]>sum/cnt){
	printf("%d\n"),number[i];
}
```



### 提问：

**这个程序存在什么安全隐患？**



## 出现的问题

1. while 循环不符合条件及退出

​	   for 循环遍历，结合if语句将符合条件的值输出

2. 