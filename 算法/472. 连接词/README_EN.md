| English | [简体中文](README.md) |

# [472. Concatenated Words](https://leetcode.cn/problems/concatenated-words)
 ### Description
<p>Given an array of strings <code>words</code> (<strong>without duplicates</strong>), return <em>all the <strong>concatenated words</strong> in the given list of</em> <code>words</code>.</p>

<p>A <strong>concatenated word</strong> is defined as a string that is comprised entirely of at least two shorter words (not necesssarily distinct)&nbsp;in the given array.</p>

<p>&nbsp;</p>
<p><strong class="example">Example 1:</strong></p>

<pre>
<strong>Input:</strong> words = [&quot;cat&quot;,&quot;cats&quot;,&quot;catsdogcats&quot;,&quot;dog&quot;,&quot;dogcatsdog&quot;,&quot;hippopotamuses&quot;,&quot;rat&quot;,&quot;ratcatdogcat&quot;]
<strong>Output:</strong> [&quot;catsdogcats&quot;,&quot;dogcatsdog&quot;,&quot;ratcatdogcat&quot;]
<strong>Explanation:</strong> &quot;catsdogcats&quot; can be concatenated by &quot;cats&quot;, &quot;dog&quot; and &quot;cats&quot;; 
&quot;dogcatsdog&quot; can be concatenated by &quot;dog&quot;, &quot;cats&quot; and &quot;dog&quot;; 
&quot;ratcatdogcat&quot; can be concatenated by &quot;rat&quot;, &quot;cat&quot;, &quot;dog&quot; and &quot;cat&quot;.</pre>

<p><strong class="example">Example 2:</strong></p>

<pre>
<strong>Input:</strong> words = [&quot;cat&quot;,&quot;dog&quot;,&quot;catdog&quot;]
<strong>Output:</strong> [&quot;catdog&quot;]
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= words.length &lt;= 10<sup>4</sup></code></li>
	<li><code>1 &lt;= words[i].length &lt;= 30</code></li>
	<li><code>words[i]</code> consists of only lowercase English letters.</li>
	<li>All the strings of <code>words</code> are <strong>unique</strong>.</li>
	<li><code>1 &lt;= sum(words[i].length) &lt;= 10<sup>5</sup></code></li>
</ul>

**Related Topics**  [Depth-First Search](https://leetcode.cn/tag/depth-first-search) [Trie](https://leetcode.cn/tag/trie) [Array](https://leetcode.cn/tag/array) [String](https://leetcode.cn/tag/string) [Dynamic Programming](https://leetcode.cn/tag/dynamic-programming) 

### Similar Questions
