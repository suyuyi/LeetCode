[39.Combination Sum](https://leetcode-cn.com/problems/combination-sum/)  
这道题比较有意思，我对DP的认识都是停留在一个一维/二维/多维的数组上的，也就是dp数组记录的是上一个情况的某些状态  
换而言之，我经常用dp求方案数、是否可行，但具体的方案我不太清楚该怎么获取，因此我先用了一个dfs+回溯的方案，估计样例不太严格，没卡时间，侥幸通过了    
这一题的关键是方案不能重复，因此将dfs如何划分很关键，采取划分方式：
* 选取该位置，target减去该位置的值
* 不选取，同时跳过该位置，此后不会再选择该位置

这样两个分支的方案就不会重复，代码如下：  
```Java
class Solution {
    static List<Integer> ans = new ArrayList<>();
    static List<List<Integer>> res = new ArrayList<>();
    public List<List<Integer>> combinationSum(int[] candidates, int target) {
        ans.clear();res.clear();
        List<Integer> _candidates = new ArrayList<>();
        for(int i:candidates) _candidates.add(i);
        dfs(_candidates,target);
        return res;
    }
    public void dfs(List<Integer> candidates, int target){
        if(candidates.size()==0) return;
        if(target==0){
            List<Integer> tmp = new ArrayList<>();
            for(Integer i:ans) tmp.add(i);
            res.add(tmp);
            return;
        }
        else if(target<0) return;
        // target > 0
        int num =candidates.get(0);
        dfs(candidates.subList(1,candidates.size()),target);
        ans.add(num);
        dfs(candidates,target-num);
        ans.remove(ans.size()-1);
    }
}
```  
*PS:原本以为有DP的，结果看答案好像就是dfs回溯+剪枝，无语了*😶
