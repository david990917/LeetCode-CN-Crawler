| English | [简体中文](README.md) |

# [面试题 16.09. Operations LCCI](https://leetcode.cn/problems/operations-lcci)
 ### Description
<p>Write methods to implement the multiply, subtract, and divide operations for integers. The results of all of these are integers. Use only the add operator.</p>

<p>You should implement following methods:</p>

<ul>
	<li><code>Operations()</code>&nbsp; constructor</li>
	<li><code>minus(a, b)</code>&nbsp; Subtraction, returns&nbsp;<code>a - b</code></li>
	<li><code>multiply(a, b)</code>&nbsp; Multiplication, returns&nbsp;<code>a * b</code></li>
	<li><code>divide(a, b)</code>&nbsp; Division, returns&nbsp;<code>a / b</code></li>
</ul>

<p><strong>Example: </strong></p>

<pre>
Operations operations = new Operations();
operations.minus(1, 2); //returns -1
operations.multiply(3, 4); //returns 12
operations.divide(5, -2); //returns -2
</pre>

<p><strong>Note: </strong></p>

<ul>
	<li>You can assume inputs are always valid, that is, e.g., denominator will not be 0 in division.</li>
	<li>The number of calls will not exceed 1000.</li>
</ul>

**Related Topics**  [Design](https://leetcode.cn/tag/design) [Math](https://leetcode.cn/tag/math) 