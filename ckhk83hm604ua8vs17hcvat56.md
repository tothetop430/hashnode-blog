---
title: "Python (NEW) Print ?"
datePublished: Mon Nov 16 2020 06:26:36 GMT+0000 (Coordinated Universal Time)
cuid: ckhk83hm604ua8vs17hcvat56
slug: python-new-print
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1607154264034/Y1L8Tj8yr.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1609400112264/fRdwVHi9K.png
tags: programming-blogs, python, opensource, coding

---

Recently, Guido Van Rossum (Creator of Python) presented python community with the idea of new print statement !

When Python 3 replaced print statement (Python 2) with print() function, many felt the transition is smooth and adaptable compared to other changes.

As of now, Python 2 is the legacy version and Van Rossum presents an updated print statement !

```
>>> print 1+6
7
```
Hmm, Nothing New !!

The new parser for print statement has the power to make ANY function in python to be used as a statement.

Yes, ANY function/method can be used as a statement !

```
>>> len ‘abc’
3
```

```
>>> import random
>>> random.randint 2, 5
4
```

How crazy is that !!

It is not just new print statement but a new way to look at python statements.

But, it comes with a drawback.

```
>>> print (2), 10
2
(None, 10)
```

Here the parser consider print(2) as function first, then evaluates return of print function (None) and 10 as a tuple, hence the output.

Anyway, it is really amazing to see generic way of using statements in-place of other functions !

Would you love to use a python statement over a function ? If not, why is that ?

---

Just starting you Open Source Journey ? Don't forget to check out [Hello Open Source](https://github.com/siddharth2016/hello-open-source)

Want to `++` your GitHub Profile README ? Check out [Quote - README](https://github.com/marketplace/actions/quote-readme)

Want to make a simple and awesome game from scratch ? Check [PongPong](https://github.com/siddharth2016/PongPong)

Till next time !

Namaste 🙏