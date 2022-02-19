# 十一、`str_contains`

日期:2020 年 2 月 17 日

作者:菲利普·坦拉克

票数:43 票/ 9 票

我想知道你们当中有多少人正在阅读这篇文章，他们的代码库中有一个临时的函数，名字和功能都很相似。在研究这本书的时候，我告诉了一个同事这个功能，他接着向我展示了我日常使用的代码库中的一个`str_contains`功能！不用说，PHP 需要这一点已经有一段时间了。顾名思义，如果一个字符串包含在另一个给定的字符串中，这个函数返回`true/false`。和许多其他 PHP 函数一样，这是以`($haystack, $needle)`的形式。

```php
<?php

str_contains("hive", "v"); // true
str_contains("brodels", "z"); // false

// using an empty string as $needle
str_contains("hive", "");  // true
str_contains("", "");     // true

```

尽管有九张反对票，内部邮件列表上的讨论非常少，而且大多是积极的。