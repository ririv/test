# 锚点

## `.md` 后缀，链接Markdown文件

[file](file) ×

[file.md](file.md) √

[file#head](file#head) ×

[file.md#head](file.md#head) √



## 无 `.md` 后缀，链接同名文件夹下所显示的 README.md （并没有进入此文件）

[dir](dir) √

[dir#head ](dir#head) √



## 省略标点符号

未省略 `.`：[head.a](file.md#head.a)

省略 `.`：[heada](file.md#heada)



未省略 空格：[head b](file.md#head b)

省略 空格：[headb](file.md#headb)



未省略 反引号：[`headc`](file.md#`headc`)

省略 反引号：[headc](file.md#headc)



未省略  `-`：[head-d](file.md#head-d)

省略 `-`：[headd](file.md#headd)



# 图片

`.assets` 文件夹 √

![yuki](.assets/img-1.jpg)

`assets` 文件夹 √

![yuki](assets/img-2.jpg)

