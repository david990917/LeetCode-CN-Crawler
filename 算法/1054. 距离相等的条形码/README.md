| [English](README_EN.md) | 简体中文 |

# [1054. 距离相等的条形码](https://leetcode.cn/problems/distant-barcodes)
<p>在一个仓库里，有一排条形码，其中第 <code>i</code> 个条形码为&nbsp;<code>barcodes[i]</code>。</p>

<p>请你重新排列这些条形码，使其中任意两个相邻的条形码不能相等。 你可以返回任何满足该要求的答案，此题保证存在答案。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>barcodes = [1,1,1,2,2,2]
<strong>输出：</strong>[2,1,2,1,2,1]
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>barcodes = [1,1,1,1,2,2,3,3]
<strong>输出：</strong>[1,3,1,3,2,1,2,1]</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= barcodes.length &lt;= 10000</code></li>
	<li><code>1 &lt;= barcodes[i] &lt;= 10000</code></li>
</ul>

**标签:**  [贪心](https://leetcode.cn/tag/greedy) [数组](https://leetcode.cn/tag/array) [哈希表](https://leetcode.cn/tag/hash-table) [计数](https://leetcode.cn/tag/counting) [排序](https://leetcode.cn/tag/sorting) [堆（优先队列）](https://leetcode.cn/tag/heap-priority-queue) 