| [English](README_EN.md) | 简体中文 |

# [610. 判断三角形](https://leetcode.cn/problems/triangle-judgement)
<p>表:&nbsp;<code>Triangle</code></p>

<pre>
+-------------+------+
| Column Name | Type |
+-------------+------+
| x           | int  |
| y           | int  |
| z           | int  |
+-------------+------+
(x, y, z)是该表的主键列。
该表的每一行包含三个线段的长度。
</pre>

<p>&nbsp;</p>

<p>写一个SQL查询，每三个线段报告它们是否可以形成一个三角形。</p>

<p>以&nbsp;<strong>任意顺序&nbsp;</strong>返回结果表。</p>

<p>查询结果格式如下所示。</p>

<p>&nbsp;</p>

<p><strong>示例 1:</strong></p>

<pre>
<strong>输入:</strong> 
Triangle 表:
+----+----+----+
| x  | y  | z  |
+----+----+----+
| 13 | 15 | 30 |
| 10 | 20 | 15 |
+----+----+----+
<strong>输出:</strong> 
+----+----+----+----------+
| x  | y  | z  | triangle |
+----+----+----+----------+
| 13 | 15 | 30 | No       |
| 10 | 20 | 15 | Yes      |
+----+----+----+----------+</pre>

**标签:**  [数据库](https://leetcode.cn/tag/database) 