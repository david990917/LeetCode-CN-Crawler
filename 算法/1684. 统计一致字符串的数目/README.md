| [English](README_EN.md) | 简体中文 |

# [1684. 统计一致字符串的数目](https://leetcode.cn/problems/count-the-number-of-consistent-strings)
<p>给你一个由不同字符组成的字符串 <code>allowed</code> 和一个字符串数组 <code>words</code> 。如果一个字符串的每一个字符都在 <code>allowed</code> 中，就称这个字符串是 <strong>一致字符串 </strong>。</p>

<p>请你返回 <code>words</code> 数组中 <strong>一致字符串</strong> 的数目。</p>

<p> </p>

<p><strong>示例 1：</strong></p>

<pre>
<b>输入：</b>allowed = "ab", words = ["ad","bd","aaab","baa","badab"]
<b>输出：</b>2
<b>解释：</b>字符串 "aaab" 和 "baa" 都是一致字符串，因为它们只包含字符 'a' 和 'b' 。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<b>输入：</b>allowed = "abc", words = ["a","b","c","ab","ac","bc","abc"]
<b>输出：</b>7
<b>解释：</b>所有字符串都是一致的。
</pre>

<p><strong>示例 3：</strong></p>

<pre>
<b>输入：</b>allowed = "cad", words = ["cc","acd","b","ba","bac","bad","ac","d"]
<b>输出：</b>4
<b>解释：</b>字符串 "cc"，"acd"，"ac" 和 "d" 是一致字符串。
</pre>

<p> </p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 <= words.length <= 10<sup>4</sup></code></li>
	<li><code>1 <= allowed.length <=<sup> </sup>26</code></li>
	<li><code>1 <= words[i].length <= 10</code></li>
	<li><code>allowed</code> 中的字符 <strong>互不相同</strong> 。</li>
	<li><code>words[i]</code> 和 <code>allowed</code> 只包含小写英文字母。</li>
</ul>

**标签:**  [位运算](https://leetcode.cn/tag/bit-manipulation) [数组](https://leetcode.cn/tag/array) [哈希表](https://leetcode.cn/tag/hash-table) [字符串](https://leetcode.cn/tag/string) 