#### 剑指 Offer 59 - I. 滑动窗口的最大值
-  边界情况 数组为空或者窗口为0 
`if(nums.length == 0 || k == 0) return new int[0];`
- 使用链表实现的双端队列的创建
  `Deque<Integer> deque = new LinkedList<>();`
