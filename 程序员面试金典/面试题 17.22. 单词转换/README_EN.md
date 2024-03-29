| English | [简体中文](README.md) |

# [面试题 17.22. Word Transformer LCCI](https://leetcode.cn/problems/word-transformer-lcci)
 ### Description
<p>Given two words of equal length that are in a dictionary, write a method to transform one word into another word by changing only one letter at a time. The new word you get in each step must be in the dictionary.</p>

<p>Write code to return a possible transforming sequence. If there is more than one sequence, return any of them.</p>

<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong>
beginWord = &quot;hit&quot;,
endWord = &quot;cog&quot;,
wordList = [&quot;hot&quot;,&quot;dot&quot;,&quot;dog&quot;,&quot;lot&quot;,&quot;log&quot;,&quot;cog&quot;]

<strong>Output:</strong>
[&quot;hit&quot;,&quot;hot&quot;,&quot;dot&quot;,&quot;lot&quot;,&quot;log&quot;,&quot;cog&quot;]
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong>
beginWord = &quot;hit&quot;
endWord = &quot;cog&quot;
wordList = [&quot;hot&quot;,&quot;dot&quot;,&quot;dog&quot;,&quot;lot&quot;,&quot;log&quot;]

<strong>Output: </strong>[]

<strong>Explanation:</strong>&nbsp;<em>endWord</em> &quot;cog&quot; is not in the dictionary, so there&#39;s no possible transforming sequence.</pre>

**Related Topics**  [Breadth-First Search](https://leetcode.cn/tag/breadth-first-search) [Hash Table](https://leetcode.cn/tag/hash-table) [String](https://leetcode.cn/tag/string) [Backtracking](https://leetcode.cn/tag/backtracking) 