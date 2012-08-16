---
layout: blog
title: New Chapter! The compress Package
---

## {{ page.title }}

<small>{{ page.date | date_to_long_string }}</small>

---

Have big things that you need to make smaller? Look no further than the `compress` package. It's the next chapter available in [Go, The Standard Library](/go.html).

Since each sub-package in the `compress` package follows basically the same interface, I tried something different this time. I used the `flag` package (which we'll see later) to control what to do. The main example file uses all the different compression packages in one foul swoop, instead of separate files for each algorithm. The `crypto` package will be similar.

I also included a good real-world example: **Accept-Encoding: gzip**

It looks at building `gzip` support into your webserver. It's super simple thanks to how Go deals with IO.

Anyway, if you want to check it out, [get your copy of Go, The Standard Library](/go.html) now for only **${{ site.go.price }}**. The book's only getting bigger!
