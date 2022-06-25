[剑指 Offer II 091. 粉刷房子](https://leetcode.cn/problems/JEj789/)  
一道涉及状态机的DP问题，值得思考一下如何证明状态机的状态变换不会忽略其他最优解
```java
public int minCost(int[][] costs) {
    /**
     * a -> d
     * b -> e
     * c -> f
     */
    int a=costs[0][0], b=costs[0][1],c=costs[0][2];
    for(int i=1;i<costs.length;++i){
        int d,e,f;
        d = Math.min(b,c)+costs[i][0];
        e = Math.min(a,c)+costs[i][1];
        f = Math.min(a,b)+costs[i][2];
        a=d;b=e;c=f;
    }
    return Math.min(a,Math.min(b,c));
}
```
