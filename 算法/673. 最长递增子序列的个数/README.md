| [English](README_EN.md) | 简体中文 |

# [673. 最长递增子序列的个数](https://leetcode.cn/problems/number-of-longest-increasing-subsequence)
<p>给定一个未排序的整数数组<meta charset="UTF-8" />&nbsp;<code>nums</code>&nbsp;，&nbsp;<em>返回最长递增子序列的个数</em>&nbsp;。</p>

<p><strong>注意</strong>&nbsp;这个数列必须是 <strong>严格</strong> 递增的。</p>

<p>&nbsp;</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> [1,3,5,4,7]
<strong>输出:</strong> 2
<strong>解释:</strong> 有两个最长递增子序列，分别是 [1, 3, 4, 7] 和[1, 3, 5, 7]。
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> [2,2,2,2,2]
<strong>输出:</strong> 5
<strong>解释:</strong> 最长递增子序列的长度是1，并且存在5个子序列的长度为1，因此输出5。
</pre>

<p>&nbsp;</p>

<p><strong>提示:</strong>&nbsp;</p>

<p><meta charset="UTF-8" /></p>

<ul>
	<li><code>1 &lt;= nums.length &lt;= 2000</code></li>
	<li><code>-10<sup>6</sup>&nbsp;&lt;= nums[i] &lt;= 10<sup>6</sup></code></li>
</ul>

**标签:**  [树状数组](https://leetcode.cn/tag/binary-indexed-tree) [线段树](https://leetcode.cn/tag/segment-tree) [数组](https://leetcode.cn/tag/array) [动态规划](https://leetcode.cn/tag/dynamic-programming) 