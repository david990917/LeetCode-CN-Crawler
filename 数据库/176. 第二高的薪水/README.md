| [English](README_EN.md) | 简体中文 |

# [176. 第二高的薪水](https://leetcode.cn/problems/second-highest-salary)
<code>Employee</code> 表：
<div class="original__bRMd">
<div>
<pre>
+-------------+------+
| Column Name | Type |
+-------------+------+
| id          | int  |
| salary      | int  |
+-------------+------+
id 是这个表的主键。
表的每一行包含员工的工资信息。
</pre>

<p>&nbsp;</p>

<p>编写一个 SQL 查询，获取并返回 <code>Employee</code>&nbsp;表中第二高的薪水 。如果不存在第二高的薪水，查询应该返回 <code>null</code> 。</p>

<p>查询结果如下例所示。</p>

<p>&nbsp;</p>

<p><strong>示例 1：</strong></p>

<pre>
<strong>输入：</strong>
Employee 表：
+----+--------+
| id | salary |
+----+--------+
| 1  | 100    |
| 2  | 200    |
| 3  | 300    |
+----+--------+
<strong>输出：</strong>
+---------------------+
| SecondHighestSalary |
+---------------------+
| 200                 |
+---------------------+
</pre>

<p><strong>示例 2：</strong></p>

<pre>
<strong>输入：</strong>
Employee 表：
+----+--------+
| id | salary |
+----+--------+
| 1  | 100    |
+----+--------+
<strong>输出：</strong>
+---------------------+
| SecondHighestSalary |
+---------------------+
| null                |
+---------------------+
</pre>
</div>
</div>

**标签:**  [数据库](https://leetcode.cn/tag/database) 