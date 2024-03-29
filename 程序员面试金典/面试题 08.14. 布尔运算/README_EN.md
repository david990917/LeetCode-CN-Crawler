| English | [简体中文](README.md) |

# [面试题 08.14. Boolean Evaluation LCCI](https://leetcode.cn/problems/boolean-evaluation-lcci)
 ### Description
<p>Given a boolean expression consisting of the symbols <code>0</code> (false), <code>1</code> (true), <code>&amp;</code> (AND), <code>|</code> (OR), and <code>^</code>&nbsp;(XOR), and a desired boolean result value result, implement a function to count the number of ways of parenthesizing the expression such that it evaluates to result.</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input: </strong>s = &quot;1^0|0|1&quot;, result = 0

<strong>Output: </strong>2
<strong>Explanation:</strong>&nbsp;Two possible parenthesizing ways are:
1^(0|(0|1))
1^((0|0)|1)
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input: </strong>s = &quot;0&amp;0&amp;0&amp;1^1|0&quot;, result = 1

<strong>Output: </strong>10</pre>

<p><strong>Note: </strong></p>

<ul>
	<li>There are no more than&nbsp;19 operators in <code>s</code>.</li>
</ul>

**Related Topics**  [Memoization](https://leetcode.cn/tag/memoization) [String](https://leetcode.cn/tag/string) [Dynamic Programming](https://leetcode.cn/tag/dynamic-programming) 