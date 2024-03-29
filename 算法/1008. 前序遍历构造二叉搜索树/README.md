| [English](README_EN.md) | 简体中文 |

# [1008. 前序遍历构造二叉搜索树](https://leetcode.cn/problems/construct-binary-search-tree-from-preorder-traversal)
<p>给定一个整数数组，它表示BST(即 <strong>二叉搜索树</strong> )的 <strong>先</strong><strong>序遍历</strong> ，构造树并返回其根。</p>

<p><strong>保证</strong> 对于给定的测试用例，总是有可能找到具有给定需求的二叉搜索树。</p>

<p><strong>二叉搜索树</strong> 是一棵二叉树，其中每个节点，&nbsp;<code>Node.left</code>&nbsp;的任何后代的值 <strong>严格小于</strong> <code>Node.val</code>&nbsp;,&nbsp;<code>Node.right</code>&nbsp;的任何后代的值 <strong>严格大于</strong> <code>Node.val</code>。</p>

<p>二叉树的 <strong>前序遍历</strong> 首先显示节点的值，然后遍历<code>Node.left</code>，最后遍历<code>Node.right</code>。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<p><img src="https://assets.leetcode.com/uploads/2019/03/06/1266.png" /></p>

<pre>
<strong>输入：</strong>preorder = [8,5,1,7,10,12]
<strong>输出：</strong>[8,5,10,1,7,null,12]
</pre>

<p><strong>示例 2:</strong></p>

<pre>
<strong>输入:</strong> preorder = [1,3]
<strong>输出:</strong> [1,null,3]
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li><code>1 &lt;= preorder.length &lt;= 100</code></li>
	<li><code>1 &lt;= preorder[i]&nbsp;&lt;= 10^8</code></li>
	<li><code>preorder</code> 中的值 <strong>互不相同</strong></li>
</ul>

<p>&nbsp;</p>

**标签:**  [栈](https://leetcode.cn/tag/stack) [树](https://leetcode.cn/tag/tree) [二叉搜索树](https://leetcode.cn/tag/binary-search-tree) [数组](https://leetcode.cn/tag/array) [二叉树](https://leetcode.cn/tag/binary-tree) [单调栈](https://leetcode.cn/tag/monotonic-stack) 