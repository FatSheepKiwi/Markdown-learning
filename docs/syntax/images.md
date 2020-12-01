# 图像

插入图片的语法和插入超链接的语法基本一致，只是在最前面多一个 `!`。也分为行内式和参考式两种。

## 行内式

```markdown
![ Lorem Picsum](https://picsum.photos/200/300 " Lorem Picsum Photo")
```

![ Lorem Picsum](https://picsum.photos/200/300 " Lorem Picsum Photo")

方括号中的部分是图片的替代文本，括号中的 'title' 部分和链接一样，是可选的。

## 参考式

```markdown
![ Lorem Picsum][lorem]

[lorem]: https://picsum.photos/200/300 "Lorem Picsum Photo"
```

![ Lorem Picsum][lorem]

[lorem]: https://picsum.photos/200/300 "Lorem Picsum Photo"

参考式的好处是可以对图片链接进行统一管理，方便未来编辑。

## 指定图片的显示大小

Markdown 不支持指定图片的显示大小，不过可以通过直接插入`<img />`标签来指定相关属性：

```html
<img src="https://picsum.photos/200/300" alt="GitHub" title="Lorem Picsum Photo" width="50" height="50" />
```

<img src="https://picsum.photos/200/300" alt="GitHub" title="Lorem Picsum Photo" width="50" height="50" />
