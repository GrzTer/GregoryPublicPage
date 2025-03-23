---
title: group-anagrams
draft: false
tags:
  - leetcode
  - neetcode
  - anagram
  - medium
---
# [49. Group Anagrams](https://leetcode.com/problems/group-anagrams/)

Given an array of strings `strs`, group the anagrams together. You can return the answer in **any order**.

**Example 1:**

**Input:** strs = `["eat","tea","tan","ate","nat","bat"]`

**Output:** `[["bat"],["nat","tan"],["ate","eat","tea"]]`

**Explanation:**

- There is no string in strs that can be rearranged to form `"bat"`.
- The strings `"nat"` and `"tan"` are anagrams as they can be rearranged to form each other.
- The strings `"ate"`, `"eat"`, and `"tea"` are anagrams as they can be rearranged to form each other.

**Example 2:**

**Input:** strs = `[""]`

**Output:**` [[""]]`

**Example 3:**

**Input:** strs = `["a"]`

**Output:** `[["a"]]`

**Constraints:**

- `1 <= strs.length <= 104`
- `0 <= strs[i].length <= 100`
- `strs[i]` consists of lowercase English letters.

---
## Starter
```python
class Solution(object):
    def groupAnagrams(self, strs):
        """

        :type strs: List[str]
        :rtype: List[List[str]]

        """
```

---
## Code

```python

```
%% 
1. First of all I need to initialize a list that will contain a solution
2. Sort all elements of `strs`
3. Make a `For` loop that will select each index of this list.
	1. Sort each `string` i
	2. With`For` loop check if an `string` i is similar to any other object using === 
	3. Append string in solo list if there is none / Append string in multi list if there is multiple instances of said string
4. Return list %%

- Initialize 