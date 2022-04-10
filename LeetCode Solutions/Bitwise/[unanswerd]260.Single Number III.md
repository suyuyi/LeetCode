[260. Single Number III](https://leetcode-cn.com/problems/single-number-iii/)  
首先将全部数组元素异或，由于两个元素只出现一次，因此二者不可能相等，必然有一个bit不相等，因此可以通过lowbit找到低位第一个不同的bit，然后以此将元素分为两类：  
* 该bit为0的
* 该bit为1的  

这两类元素互不相交，因此各取异或，则可以分别得到其中只包含一个的元素，代码如下：
```java
class Solution {
    public int[] singleNumber(int[] nums) {
        int xorsum=0;
        for(int i:nums) xorsum^=i;
        int lowbit = (xorsum==Integer.MIN_VALUE)?xorsum:(xorsum&-xorsum);
        int[] res = new int[2];
        for(int i:nums){
            if((i&lowbit)!=0) res[0]^=i;
            else res[1]^=i;
        }
        return res;
    }
}
```
**疑问**
* 如果包含三个乃至多个互不相同的元素？
