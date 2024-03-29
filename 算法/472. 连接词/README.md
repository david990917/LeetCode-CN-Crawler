| [English](README_EN.md) | 简体中文 |

# [472. 连接词](https://leetcode.cn/problems/concatenated-words)
<p>给你一个 <strong>不含重复 </strong>单词的字符串数组 <code>words</code> ，请你找出并返回 <code>words</code> 中的所有 <strong>连接词</strong> 。</p>

<p><strong>连接词</strong> 定义为：一个完全由给定数组中的至少两个较短单词（不一定是不同的两个单词）组成的字符串。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>words = ["cat","cats","catsdogcats","dog","dogcatsdog","hippopotamuses","rat","ratcatdogcat"]
<strong>输出：</strong>["catsdogcats","dogcatsdog","ratcatdogcat"]
<strong>解释：</strong>"catsdogcats" 由 "cats", "dog" 和 "cats" 组成; 
     "dogcatsdog" 由 "dog", "cats" 和 "dog" 组成; 
     "ratcatdogcat" 由 "rat", "cat", "dog" 和 "cat" 组成。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>words = ["cat","dog","catdog"]
<strong>输出：</strong>["catdog"]</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= words.length &lt;= 10<sup>4</sup></code></li>
	<li><code>1 &lt;= words[i].length &lt;= 30</code></li>
	<li><code>words[i]</code>&nbsp;仅由小写英文字母组成。</li>
	<li>&nbsp;<code>words</code>&nbsp;中的所有字符串都是 <strong>唯一</strong> 的。</li>
	<li><code>1 &lt;= sum(words[i].length) &lt;= 10<sup>5</sup></code></li>
</ul>

**标签:**  [深度优先搜索](https://leetcode.cn/tag/depth-first-search) [字典树](https://leetcode.cn/tag/trie) [数组](https://leetcode.cn/tag/array) [字符串](https://leetcode.cn/tag/string) [动态规划](https://leetcode.cn/tag/dynamic-programming) 