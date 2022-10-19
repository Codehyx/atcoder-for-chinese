## 题意

判断是否存在一个由 $1$ 到 $N$ 组成的排列满足 $M$ 个形如 $A_i$ 和 $B_i$ 必须相邻的条件。

## 数据范围

- $2 \le N \le 10^5$
- $0 \le M \le 10^5$
- $1 \le A_i < B_i \le N$
- 每一对 $(A_i,B_i)$ 都互不相同。

## 输入格式

第一行两个正整数 $N,M$ 表示排列的长度和条件的个数。  
接下来 $M$ 行每行两个正整数 $A_i,B_i$ 表示一个条件。

## 输出格式

如果存在合法的排列则输出 `Yes`，否则输出 `No`。

## 样例

### 样例输入1

```input
4 2
1 3
2 3

```

### 样例输出1

```output
Yes

```

### 样例解释1

其中一种符合条件的排列为 $4,1,3,2$。

### 样例输入2

```input
4 3
1 4
2 4
3 4

```

### 样例输出2

```output
No

```