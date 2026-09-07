# leetcode-cpp
1
遍历到 nums[i] 时，计算需要的另一个数：need = target - nums[i]。
在哈希表中查找 need。
如果找到，返回两个元素的下标。
如果没找到，将当前数及其下标保存到哈希表。
