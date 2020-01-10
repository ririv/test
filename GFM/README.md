# 锚点

## `.md` 后缀

### `.md` 后缀，链接Markdown文件

[file](file) ×

[file.md](file.md) √

[file#head](file#head) ×

[file.md#head](file.md#head) √



### 无 `.md` 后缀，链接同名文件夹下所显示的 README.md （并没有进入此文件）

[dir](dir) √

[dir#head ](dir#head) √



## 省略标点符号

未省略 `.`：[head.a](file.md#head.a) ×

省略 `.`：[heada](file.md#heada) √

  


未省略 空格：[head b](file.md#head b) ×

文字未省略 空格，但链接省略 空格：[head b](file.md#headb) ×

文字省略 空格，但链接未省略 空格：[headb](file.md#head b) ×

省略 空格：[headb](file.md#headb) ×

`-` 代替链接空格：[head b](file.md#head-b) √

  



未省略 反引号：[`headc`](file.md#`headc`) ×

省略 反引号：[headc](file.md#headc) √

  


未省略  `-`：[head-d](file.md#head-d) √

省略 `-`：[headd](file.md#headd) ×

   


空格与 `-` 混合使用：[head e-x](file.md#head-e-x) √

  

去掉除 `-` 以外的标点符号，如 `.`、反引号：[1.test-`x`](file.md#1test-x)



## 大写转换小写

转换：[HEADF](file.md#headf) √

未转换：[HEADF](file.md#HEADF) √



## 混合测试

[1.2. AB 标题-`x`](file.md#12-Ab-标题-x)



# 图片

`.assets` 文件夹 √

![img](.assets/img-1.jpg)

`assets` 文件夹 √

![](assets/img-2.jpg)

