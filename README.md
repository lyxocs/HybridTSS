# NeuroTSS
NeuroTSS

## 20220728更新
移除冗余文件， 增加注释

## 20220729更新
后续一些优化方案记录
1. 在平衡内存的前提下，引入Cache加快训练速度
2. 重新设计state编码，使得单个维度可以多次选择
3. 对于最终节点仍为Tuple类型的节点，考虑引入PartitionSort/NuevoMatch(iSet)类似的贪心算法，进一步优化，尽可能远离TSS类算法