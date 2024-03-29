| English | [简体中文](README.md) |

# [面试题 04.10. Check SubTree LCCI](https://leetcode.cn/problems/check-subtree-lcci)
 ### Description
<p>T1&nbsp;and T2 are two very large binary trees. Create an algorithm to determine if T2 is a subtree of T1.</p>

<p>A tree T2 is a subtree of T1&nbsp;if there exists a node n in T1&nbsp;such that the subtree of n is identical to T2. That is, if you cut off the tree at node n, the two trees would be identical.</p>

<p><strong>Note:</strong> This problem is slightly different from the original problem.</p>

<p><strong>Example1:</strong></p>

<pre>
<strong> Input</strong>: t1 = [1, 2, 3], t2 = [2]
<strong> Output</strong>: true
</pre>

<p><strong>Example2:</strong></p>

<pre>
<strong> Input</strong>: t1 = [1, null, 2, 4], t2 = [3, 2]
<strong> Output</strong>: false
</pre>

<p><strong>Note: </strong></p>

<ol>
	<li>The node numbers of both tree are in [0, 20000].</li>
</ol>

**Related Topics**  [Tree](https://leetcode.cn/tag/tree) [Depth-First Search](https://leetcode.cn/tag/depth-first-search) [Binary Tree](https://leetcode.cn/tag/binary-tree) [String Matching](https://leetcode.cn/tag/string-matching) [Hash Function](https://leetcode.cn/tag/hash-function) 