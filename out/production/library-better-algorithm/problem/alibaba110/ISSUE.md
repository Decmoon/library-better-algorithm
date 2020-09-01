概述
-  
> 给出一个长度为 n 的数组，和一个正整数 d。<br/>
你每次可以选择其中任意一个元素 a[i] 将其变为 a[i] + d 或 a[i] - d，这算作一次操作。<br/>
你需要将所有的元素全部变成相等元素，如果有解，请输出最小操作次数，如果无解请输出-1。<br/>
<br/>
 输入数字n、数字d，和一个长度为n的数组a。<br/>
 1 <= n <= 100000，1 <= d <= 100, 1 <= a[i] <= 100000。<br/>
输出一个数字，表示最小的操作次数，如果无解输出-1。
  
+ 示例
````=
输入：
5
2
3,5,7,1,9

输出：
6
````
+ 注意
 
 最优解为全部变为5，共1 + 0 + 1 + 2 + 2 = 6次。
  
取自
-
 [阿里云开发者社区 在线编程110 - 数组变换](https://developer.aliyun.com/coding/110)