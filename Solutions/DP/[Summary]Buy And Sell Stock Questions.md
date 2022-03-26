# 有关于股票售卖的问题总集
[121. Best Time to Buy and Sell Stock](https://leetcode-cn.com/problems/best-time-to-buy-and-sell-stock/)

首先看题1 <= prices.length <= 10^5，暴力是O(n^2)，基本就奔着超时去了

我这边想到的首先是求**前缀和+求连续数组最大和**的方法
___
假设股票日价格为price[i]<br />
则有前缀和prefix[i] = price[i]-price[i-1]\(i>0\)<br />
prefix[i]+...+prefix[i+t] 表示i-1日买入，i+t日卖出的总利润(i>1)<br />
因此求最大的利润就是求prefixSum中的连续子数组的最大和<br />
而在求和过程中，我们只需知道某个位置前一个前缀和即可，因此无需存储<br />
另外由于只需要求最大值，因此用滚动数组节省空间<br />
代码如下：
```java
public int maxProfit(int[] prices) {
    // 滚动数组
    int[] dp= new int[2];
    dp[0] = 0;
    int ans = 0;
    for(int i=1;i<prices.length;++i){
        dp[i%2] = Math.max(prices[i]-prices[i-1],dp[(i-1)%2]+prices[i]-prices[i-1]);
        ans = Math.max(ans,dp[i%2]);
    }
    return ans;
}
```
另外看了官方解答，单调栈应该也可以实现，有兴趣可以试一下
