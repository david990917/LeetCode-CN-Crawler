| [English](README_EN.md) | 简体中文 |

# [698. 划分为k个相等的子集](https://leetcode.cn/problems/partition-to-k-equal-sum-subsets)
<p>给定一个整数数组&nbsp;&nbsp;<code>nums</code> 和一个正整数 <code>k</code>，找出是否有可能把这个数组分成 <code>k</code> 个非空子集，其总和都相等。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong> nums = [4, 3, 2, 3, 5, 2, 1], k = 4
<strong>输出：</strong> True
<strong>说明：</strong> 有可能将其分成 4 个子集（5），（1,4），（2,3），（2,3）等于总和。</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> nums = [1,2,3,4], k = 3
<strong>输出:</strong> false</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= k &lt;= len(nums) &lt;= 16</code></li>
	<li><code>0 &lt; nums[i] &lt; 10000</code></li>
	<li>每个元素的频率在 <code>[1,4]</code> 范围内</li>
</ul>

**标签:**  [位运算](https://leetcode.cn/tag/bit-manipulation) [记忆化搜索](https://leetcode.cn/tag/memoization) [数组](https://leetcode.cn/tag/array) [动态规划](https://leetcode.cn/tag/dynamic-programming) [回溯](https://leetcode.cn/tag/backtracking) [状态压缩](https://leetcode.cn/tag/bitmask) 