| [English](README_EN.md) | 简体中文 |

# [2487. 从链表中移除节点](https://leetcode.cn/problems/remove-nodes-from-linked-list)
<p>给你一个链表的头节点 <code>head</code> 。</p>

<p>对于列表中的每个节点 <code>node</code> ，如果其右侧存在一个具有 <strong>严格更大</strong> 值的节点，则移除 <code>node</code> 。</p>

<p>返回修改后链表的头节点<em> </em><code>head</code><em> </em>。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<p><img alt="" src="https://assets.leetcode.com/uploads/2022/10/02/drawio.png" style="width: 631px; height: 51px;" /></p>

<pre>
<strong>输入：</strong>head = [5,2,13,3,8]
<strong>输出：</strong>[13,8]
<strong>解释：</strong>需要移除的节点是 5 ，2 和 3 。
- 节点 13 在节点 5 右侧。
- 节点 13 在节点 2 右侧。
- 节点 8 在节点 3 右侧。
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>head = [1,1,1,1]
<strong>输出：</strong>[1,1,1,1]
<strong>解释：</strong>每个节点的值都是 1 ，所以没有需要移除的节点。
</pre>

<p>&nbsp;</p>

<p><strong>提示：</strong></p>

<ul>
	<li>给定列表中的节点数目在范围 <code>[1, 10<sup>5</sup>]</code> 内</li>
	<li><code>1 &lt;= Node.val &lt;= 10<sup>5</sup></code></li>
</ul>

**标签:**  [栈](https://leetcode.cn/tag/stack) [递归](https://leetcode.cn/tag/recursion) [链表](https://leetcode.cn/tag/linked-list) [单调栈](https://leetcode.cn/tag/monotonic-stack) 