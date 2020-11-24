# 段落与换行

1\. 段落的前后必须是空行：

空行指的是行内什么都没有，或者只有空白符（空格或制表符）

```markdown
相邻两行文本，如果中间没有空行
会显示在一行中（换行符被转换为空格）
```

相邻两行文本，如果中间没有空行
会显示在一行中（换行符被转换为空格）

```markdown
相邻两行文本，如果中间有空行

会被分成两个段落
```

相邻两行文本，如果中间有空行

会被分成两个段落

2\. 如果需要在**段落内**换行：

```markdown
段落内换行，可以使用html的 `<br>` 标签 <br>
同一段落的另一行内容
```

段落内换行，可以使用html的 `<br>` 标签 <br>
同一段落的另一行内容

```markdown
也可以在前一行的末尾加入至少两个空格  
然后换行写其它的文字
```

也可以在前一行的末尾加入至少两个空格  
然后换行写其它的文字

3\. Markdown 的多数区块依据语法规范，都需要在两个空行之间。