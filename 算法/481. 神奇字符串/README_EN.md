| English | [简体中文](README.md) |

# [481. Magical String](https://leetcode.cn/problems/magical-string)
 ### Description
<p>A magical string <code>s</code> consists of only <code>&#39;1&#39;</code> and <code>&#39;2&#39;</code> and obeys the following rules:</p>

<ul>
	<li>The string s is magical because concatenating the number of contiguous occurrences of characters <code>&#39;1&#39;</code> and <code>&#39;2&#39;</code> generates the string <code>s</code> itself.</li>
</ul>

<p>The first few elements of <code>s</code> is <code>s = &quot;1221121221221121122&hellip;&hellip;&quot;</code>. If we group the consecutive <code>1</code>&#39;s and <code>2</code>&#39;s in <code>s</code>, it will be <code>&quot;1 22 11 2 1 22 1 22 11 2 11 22 ......&quot;</code> and the occurrences of <code>1</code>&#39;s or <code>2</code>&#39;s in each group are <code>&quot;1 2 2 1 1 2 1 2 2 1 2 2 ......&quot;</code>. You can see that the occurrence sequence is <code>s</code> itself.</p>

<p>Given an integer <code>n</code>, return the number of <code>1</code>&#39;s in the first <code>n</code> number in the magical string <code>s</code>.</p>

<p>&nbsp;</p>
<p><strong class="example">Example 1:</strong></p>

<pre>
<strong>Input:</strong> n = 6
<strong>Output:</strong> 3
<strong>Explanation:</strong> The first 6 elements of magical string s is &quot;122112&quot; and it contains three 1&#39;s, so return 3.
</pre>

<p><strong class="example">Example 2:</strong></p>

<pre>
<strong>Input:</strong> n = 1
<strong>Output:</strong> 1
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= n &lt;= 10<sup>5</sup></code></li>
</ul>

**Related Topics**  [Two Pointers](https://leetcode.cn/tag/two-pointers) [String](https://leetcode.cn/tag/string) 