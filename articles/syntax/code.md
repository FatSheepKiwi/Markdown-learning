# 代码

## 代码块

### 缩进添加代码块

可以使用缩进来插入代码块：

``` markdown
    前面有空行
    每行都有tab
    后面也有空行
```

    前面有空行
    每行都有tab
    后面也有空行

代码块前后需要有至少一个空行，且每行代码前需要有至少一个 Tab 或四个空格；

### 多行代码

可以使用 \`\`\` \`\`\` 来包含多行代码，三个 \`\`\` 要独占一行。：

    ```
        <p>code here</p> 
    ```


```
<p>code here</p>
```
### 代码高亮

在上面的代码块语法基础上，在第一组 \`\`\` 之后添加代码的语言，如 'javascript' 或 'js'，即可将代码标记为 `JavaScript`：

![code-js](images/code-js.png 'JavaScript Code')

```js
window.addEventListener('load', function() {
  console.log('window loaded');
});
```

## 行内代码

也可以通过 \`\`，插入行内代码（\` 是 `Tab` 键上边、数字 `1` 键左侧的那个按键）：


``` markdown
例如 `<title>Markdown</title>`
```

例如 `<title>Markdown</title>`

## 转换规则

代码块中的文本（包括 Markdown 语法）都会显示为原始内容，而特殊字符会被转换为 HTML [字符实体](https://zh.wikipedia.org/wiki/XML%E4%B8%8EHTML%E5%AD%97%E7%AC%A6%E5%AE%9E%E4%BD%93%E5%BC%95%E7%94%A8%E5%88%97%E8%A1%A8)。
