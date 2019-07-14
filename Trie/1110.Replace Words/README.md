# 1110. Replace Words

**Description**

In English, we have a concept called `root`, which can be followed by some other words to form another longer word - let's call this word `successor`. For example, the root `an`, followed by `other`, which can form another word another.

Now, given a `dictionary` consisting of many `roots` and a `sentence`. You need to replace all the successor in the sentence with the root forming it. If a `successor` has many `roots` can form it, replace it with the root with the **shortest** length.

You need to output the sentence after the replacement.

```
The input will only have lower-case letters.
1 <= dict words number <= 1000
1 <= sentence words number <= 1000
1 <= root length <= 100
1 <= sentence words length <= 1000
```

**Example**

Example 1:

```
Input: 
dict = ["cat", "bat", "rat"]
sentence = "the cattle was rattled by the battery"
Output: 
"the cat was rat by the bat"
```

Example 2:

```
Input: 
dict = ["go", "begin", "make","end"]
sentence = "a good beginning makes a good ending"
Output: 
"a go begin make a go end"
```

**Trie**

