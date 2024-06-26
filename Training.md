| 打死不写                               |                     |      |      |      |      |
| -------------------------------------- | ------------------- | ---- | ---- | ---- | ---- |
| https://www.luogu.com.cn/problem/P6628 | 欧拉+最小生成树+... |      |      |      |      |





| 题目                                                         | 日期      | 难度           | 思路                                                         |
| ------------------------------------------------------------ | --------- | -------------- | ------------------------------------------------------------ |
| [A BIT of an Inequality](https://codeforces.com/contest/1957/problem/D) | 2024/4/24 | div2-D         | 注意到, 枚举每个中间数时, 对其最高 bit 位 1, 合法答案数量为左半区间为奇数个 1,右半为偶数个 1, 加上反情况, 用 dp 预处理. |
| [Unfair-Game](https://codeforces.com/problemset/problem/1955/F) | 4/26      | 1800           | 找到最近的 XOR=0, 此后删每次 2 个,                           |
| [Colored-Balls](https://codeforces.com/problemset/problem/1954/D) |           | 1800           | 水题                                                         |
| [Moving Both Hands](https://codeforces.com/contest/1966/problem/C) | 4/27      | Div2-C         | 别写思维了, 写一写正宗的 SG 吧!<br />把原序列去重排序, 让相邻两数的差值为新序列, 再从后往前跑 SG, 当某一位不为 1 时, 也要从 <x-1,before> ~ <1,before> 更新出来 |
| [Permutation Game](https://codeforces.com/problemset/problem/1772/E) | 4/29      | 1700           | 思维水题                                                     |
| [Lowbit](https://codeforces.com/problemset/gymProblem/103145/D) | 4/30      |                | 注意到每个数最多加 log 次, 就可以用统一的 *2 操作来维护, 所以建树维护, 同时特别标记每个数是否到达 100..00 状态, 没的话单独处理. **注意初始化和位移运算爆范围** |
| [Reverse Card (Hard Version)](https://codeforces.com/contest/1972/problem/D2) | 5/7       | Div2-D2        | 傻逼数学                                                     |
| [本初字符串](https://ac.nowcoder.com/acm/contest/82401/F)    | 5/10      | 牛客小白 F     | 推出` len(t)` 为` len(s)` 的因子, 之后枚举 `len(t)` 长度, 先找出每位取最大贡献字符组成的 `t`,再从前往后依次尝试缩小 `t[i]`. |
| [E.Increasing Subsequences](https://codeforces.com/problemset/problem/1922/E) | 5/11      | 1800           | 构造, STD::list 竟然是循环链表                               |
| [Stars](http://poj.org/problem?id=2352)                      | 5/11      |                | 树状数组处理二维偏序, 毒瘤的 POJ ! ! !                       |
| [F. Moving Points](https://codeforces.com/problemset/problem/1311/F) | 5/11      | 1900           | 不那么明显的二维偏序, 树状数组 + 离散化 处理                 |
| [B. Flipping Game](https://codeforces.com/gym/104459/problem/B) | 5/12      |                | 蛋哥的绝妙 DP, `dp[tis][i]`维护当前字符串有多少与目标字符串不同, 转移时转移到所有的可能下一层`dp[nex][i]`, and 卡 log 时间,预处理出来 inv. |
| [E.BaoBaoLovesReading](https://codeforces.com/gym/104459/problem/E) | 5/13      | 省金           | 树状数组维护每两个相同的书之间有多少种书, 种类大于 k 就要重新从书架上取, 前缀和同时维护 k=1~n 的答案. |
| [P3810[模板]三维偏序](https://www.luogu.com.cn/problem/P3810) | 5/13      | 省选 +/ NOI -  | cdq 套 树状数组处理, 也可以 cdq 套 cdq 处理                  |
| [E. Liner vectors](https://codeforces.com/gym/102801/problem/E) | 5/14      |                | 线代 ? + 构造                                                |
| [最大二分图匹配](https://www.luogu.com.cn/problem/P3386)     | 5/15      |                | 匈牙利板纸                                                   |
| [P1129 [ZJOI2007] 矩阵游戏](https://www.luogu.com.cn/problem/P1129) | 5/15      | 提高 +/ 省选 − | 注意到, 交换行列等价, 就按黑色块的 x,y 坐标连边, 跑最大二分图 |
| [K.Bracket Sequence](https://codeforces.com/gym/103486/problem/K) | 5/15      |                | 卡特兰板纸                                                   |
| [K - 树上问题](https://codeforces.com/gym/105158/problem/K)  | 5/20      |                | 树上 dp + 换根                                               |
| [D. Polycarp and Div 3](https://codeforces.com/contest/1005/problem/D) | 5/21      |                | DP                                                           |
| [ 美丽序列](https://ac.nowcoder.com/acm/contest/83524/F)     | 5/21      |                | 结论推导恶心的线段树                                         |
| [神性之陨](https://ac.nowcoder.com/acm/problem/267934)       | 5/22      |                | https://blog.nowcoder.net/n/82256070063e4a25bbbb966f3ad4fccd |
| [LH 想吃纸杯蛋糕](https://ac.nowcoder.com/acm/contest/83524/D) | 5/23      |                | DP向前枚举每位结尾合法的个数,可以注意到最多向前看 9 位, tle 不了 |
| [ 正方形的个数](https://ac.nowcoder.com/acm/contest/83524/G) | 5/24      |                | 对于每个边长与 x,y 轴平行的正方形, 可以算出在其内部且四个点都在边上的正方形的个数 |
| [ LZ的冠军之旅](https://ac.nowcoder.com/acm/contest/83524/E) | 5/24      |                | 二维费用的 djs, vis 要标记二维所有, 不能只标记一维           |
| [ 小刻的字符串](https://ac.nowcoder.com/acm/contest/83524/C) | 5/25      |                | hash 预处理, 对于每位, 向后二分找合法串                      |
| [秘境解码](https://ac.nowcoder.com/acm/contest/83524/B)      | 5/25      | 省选           | 扫描线                                                       |
| [模板-扫描线](https://www.luogu.com.cn/problem/P5490)        | 5/28      | 提高 +/ 省选 − | 扫描线板纸                                                   |
| [D.Invertible_Bracket_Sequences](https://codeforces.com/contest/1976/problem/D) | 6/3       |                | 当心 map::erase<br />括号合法不只有 num_of '(' == num_of ')'<br />还要满足每个前缀的 ( 都不少于 ) |
| [C.Turtle_and_an_Incomplete_Sequence](https://codeforces.com/contest/1981/problem/C) | 6/3       |                | 构造 + lca,不是谁家 div2-C 出构造加 lca 啊 !                 |
| [D. Turtle and Multiplication](https://codeforces.com/contest/1981/problem/D) | 6/3       |                | 构造  + 欧拉路径, 当全用质数时, 就等价于每两个数之间无重边最多连多少条边, 先给出含自环的完全图, 找最长路径, 看合法性.<br />$ \begin{cases} m为奇数 & 有最大欧拉回路 \\ m为偶数 & 2~到~m~删除一个度,有欧拉路径 \end{cases}$ |
| [P2731 [USACO3.3] 骑马修栅栏 Riding the Fences](https://www.luogu.com.cn/problem/P2731) | 6/4       | 提高 -         | SB 题                                                        |
| [D - Slimes](https://codeforces.com/contest/1923/problem/D)  | 6/5       | 1800           | 左右二分找答案, 注意长为 1 的时候没有二分性, 第一次见局部无二分性的 |
| [补给](https://www.matiji.net/exam/brushquestion/1/4498/F16DA07A4D99E21DFFEF46BD18FF68AD?from=1) | 6/5       |                | 贪心                                                         |
| [110串](https://www.matiji.net/exam/brushquestion/4/4498/F16DA07A4D99E21DFFEF46BD18FF68AD?from=1) | 6/6       |                | 计数 DP, 注意初始化到了第二位, 故第一位的答案要特判          |
| [跑步](https://www.matiji.net/exam/brushquestion/2/4498/F16DA07A4D99E21DFFEF46BD18FF68AD?from=1) | 6/6       |                | 同余环境下求 lcm                                             |
| [小度的极差](https://www.matiji.net/exam/brushquestion/5/4498/F16DA07A4D99E21DFFEF46BD18FF68AD?from=1) | 6/6       |                | SB 题                                                        |
| [D - 距离之比](https://codeforces.com/gym/105158/problem/D)  | 6/6       |                | labs 不是 abs 的 long double ! ! !<br />向量旋转后长度改变   |
| [F - Fireworks](https://codeforces.com/gym/527921/problem/F) | 6/10      |                | 双指针, 注意到 r 最多往后探 sqrt 量级                        |
| [E - L-craft (hard version)](https://codeforces.com/gym/527921/problem/E) | 6/11      |                | 世界上最屎的构造                                             |
| [D - ''a'' String Problem](https://codeforces.com/contest/1984/problem/D) | 6/12      | 2000           | 考虑以不 'a' 开头的字符串为 t 的开头, 往后枚举. 答案加上最小的前面的 'a' 的数量.<br />和谐的时间复杂度: $\sum_{i=1}^{n}\frac{n}{i}=n~logn$ |
| [D - Fixing a Binary String](https://codeforces.com/contest/1979/problem/D) | 6/12      | 1800           |                                                              |
| [B - Dfs Order 0.5](https://codeforces.com/gym/105170/problem/B) | 6/12      |                | 树形 DP, 转移时考虑贪心, 子树全为偶树, 就全取最大值, 有奇子树时, 偶子树可以取任一值, 奇子树一半取偶入口, 一半取奇入口, 多余一个取与根相反 |
| [D - Parallel Lines](https://codeforces.com/gym/105170/problem/D) | 6/13      |                | 计算几何                                                     |

