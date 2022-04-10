[40.Combination Sum II](https://leetcode-cn.com/problems/combination-sum-ii/)  
同样是一道dfs+回溯，和NO.39的不同在于这次的元素可以重复，但每个元素只允许使用一次  
简单的想法是dfs，每个元素有 选取 or 不选取 两种状态，但可能会有如下的问题，如[1,1,3]，会出现[1(第一个),3],[1(第二个),3] 这种情况，为了避免此类重复，采取如下方法：
* 先将元素数组排序
* 对一个元素，有如下两种划分  
a.选取，进入下一个  
b.不选取，跳至下一个不等于该元素的位置

如[1,1,1,1,2,3] -> 选取[1,...],不选取[2,...]
这样通过重复元素的数量可以将答案区分开，避免重复，代码如下：
```Java
class Solution {
    public List<List<Integer>> combinationSum2(int[] candidates, int target) {
        ans.clear();res.clear();
        List<Integer> _candidates = new ArrayList<>();
        Arrays.sort(candidates);
        for(int i:candidates) _candidates.add(i);
        dfs(_candidates,target);
        return res;
    }
    static List<Integer> ans = new ArrayList<>();
    static List<List<Integer>> res = new ArrayList<>();
    public void dfs(List<Integer> candidates, int target){
        if(target==0){
            List<Integer> tmp = new ArrayList<>();
            for(Integer i:ans) tmp.add(i);
            res.add(tmp);
            return;
        }
        else if(target<0) return;
        // 相比于NO.39,判断后移
        // 原因在于之前的元素可以重复选,而本次不可以
        // 如果不后移,会丢失结果
        if(candidates.size()==0) return;
        // target > 0
        int num =candidates.get(0);
        int start,end;
        start=end=0;
        while(end<candidates.size()){
            if(candidates.get(start)==candidates.get(end)) end++;
            else break;
        }
        // 不选择
        if(end != candidates.size()) dfs(candidates.subList(end,candidates.size()),target);
        ans.add(num);
        dfs(candidates.subList(1,candidates.size()),target-num);
        ans.remove(ans.size()-1);
    }
}
```
