分治法：
参照《算法导论》的讲解，要找到最大子数组，只有三种情况：    
1.最大子数组在左边    
2.最大子数组在右边
3.最大子数组在中间    
所以将一个数组切成两段，分区求最大子数组，再在此数组中间求最大子数组，找出其中的最优解    
通过层层递归，将一个大问题切分成好几个小段，这个问题就可以很好地解决
