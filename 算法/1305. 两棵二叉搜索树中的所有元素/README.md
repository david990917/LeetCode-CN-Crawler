| [English](README_EN.md) | 简体中文 |

# [1305. 两棵二叉搜索树中的所有元素](https://leetcode.cn/problems/all-elements-in-two-binary-search-trees)
<p>给你&nbsp;<code>root1</code> 和 <code>root2</code>&nbsp;这两棵二叉搜索树。请你返回一个列表，其中包含&nbsp;<strong>两棵树&nbsp;</strong>中的所有整数并按 <strong>升序</strong> 排序。.</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<p><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/12/29/q2-e1.png" /></p>

<pre>
<strong>输入：</strong>root1 = [2,1,4], root2 = [1,0,3]
<strong>输出：</strong>[0,1,1,2,3,4]
</pre>

<p><strong>示例 2：</strong></p>

<p><img alt="" src="https://assets.leetcode-cn.com/aliyun-lc-upload/uploads/2019/12/29/q2-e5-.png" /></p>

<pre>
<strong>输入：</strong>root1 = [1,null,8], root2 = [8,1]
<strong>输出：</strong>[1,1,8,8]
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li>每棵树的节点数在&nbsp;<code>[0, 5000]</code> 范围内</li>
	<li><code>-10<sup>5</sup>&nbsp;&lt;= Node.val &lt;= 10<sup>5</sup></code></li>
</ul>

**标签:**  [树](https://leetcode.cn/tag/tree) [深度优先搜索](https://leetcode.cn/tag/depth-first-search) [二叉搜索树](https://leetcode.cn/tag/binary-search-tree) [二叉树](https://leetcode.cn/tag/binary-tree) [排序](https://leetcode.cn/tag/sorting) 