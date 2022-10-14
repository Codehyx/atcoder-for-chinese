## 题意

给出一个非负整数 $N$，升序输出所有符合以下条件的非负整数 $x$：

- 设 $A_i$ 为 $i$ 在二进制表示下所有为 $1$ 的位置的集合，则 $A_x \subseteq A_N$。

## 数据范围

- $N$ 为整数。

- $0 \leq N < 2^{60}$

- $A_N$ 的元素的数量最多为 $15$。

## 输入格式

第一行输入一个整数 $N$，含义如题意所示。

## 输出格式

升序输出所有符合条件的非负整数 $x$，每行一个。

## 样例

### 样例输入1

```
11
```

### 样例输出1

```
0
1
2
3
8
9
10
11
```

### 样例解释1

$N=11_{(10)}$ 的二进制表示为 $1011_{(2)}$。

符合条件的 $x$ 分别为：

- $0000_{(2)}=0_{(10)}$

- $0001_{(2)}=1_{(10)}$

- $0010_{(2)}=2_{(10)}$

- $0011_{(2)}=3_{(10)}$

- $1000_{(2)}=8_{(10)}$

- $1001_{(2)}=9_{(10)}$

- $1010_{(2)}=10_{(10)}$

- $1011_{(2)}=11_{(10)}$

### 样例输入2

```
0
```

### 样例输出2

```
0
```

### 样例输入3

```
576461302059761664
```

### 样例输出3

```
0
524288
549755813888
549756338176
576460752303423488
576460752303947776
576461302059237376
576461302059761664
```

输入数据可能超过 `int` 所能表示的范围。