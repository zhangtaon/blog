---
title: Markdown语法说明
date: 2018-02-26 16:28:57
tags:
---
[Markdown语法说明][1]
[1]: https://www.appinn.com/markdown/index.html


>>##### 字体大小

This is an H1
=============
This is an H2
-------------
# This is 这是 H1
## This is 这是 H2
# This is 这是 H1 #
## This is 这是 H2 ##
---

>>##### 列表

1.  这是第一行列表项。
2.  这是第二行列表项。
+   这是第一行列表项。
+   这是第二行列表项。

*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.

*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,

-   Bird

-   Magic

1.  This is a list item with two paragraphs. Lorem ipsum dolor
    mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.

> This is the first level of quoting.
>
> > This is nested blockquote.


*   B list item with a blockquote:

    > This is a blockquote
    > inside a list item.

***

>>##### 特殊字符自动转换

AT&T
4 < 5
<span>zhangtao</span>

---

>>##### 代码块

    if(true){
      alert(1);
    }

`if(true){
  alert(1);
}`

`if(true){`
`alert(1);`
`}`

>     return shell_exec("echo $input | $markdown_script");

Here is an example of AppleScript:

    tell application "Foo"
        beep
    end tell

另一端代码：

    <div class="footer">
        &copy; 2004 Foo Corporation
    </div>

---

>>##### 分割线

* * *
***
*****
- - -

---------------------------------------

>>##### 链接

This is [an example](http://example.com/ "zto") inline link.

[This link](http://example.net/) has no title attribute.

See my [About](/about/) page for details.

This is [an example][id] reference-style link.

This is [an example] [id] reference-style link.

[id]: http://example.com/  "Optional Title Here"


[link text][a]
[link text][A]

[Google][]
[Google]: http://google.com/

Visit [Daring Fireball][] for more information.
[Daring Fireball]: http://daringfireball.net/

<http://example.com/>

<address@example.com>

---

>>##### 图片

![Alt text](/path/to/img.jpg)

![Alt text](/path/to/img.jpg "Optional title")

---

>>##### 强调

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__


un*frigginggbv*believable


Use the `printf()` function.


``There is a literal backtick (`) here.``

A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``  `` `jasdjkl` ``
.
Please don't use any `<blink>` tags.

`&#8212;` is the decimal-encoded equivalent of `&mdash;`.

***

>>##### 转义

\*literal asterisks\*
1986\. What a great season.
