---
layout: post
title: Định dạng văn bản
date: 2017-01-18 21:41:00
tags: jekyll
description: Các ví dụ về định dạng văn bản khi viết bài.
---

# Các ví dụ định dạng văn bản

Một số ví dụ định dạng văn bản đối với các đối tượng văn bản thông thường.

# Các tiêu đề

# Header1

## Header2

### Header3

#### Header4

##### Header5

###### Header6

# Nhấn mạnh

In nghiêng: sử dụng `*dấu sao*` -> *dấu sao* hoặc `_dấu gạch dưới_` -> _dấu gạch dưới_.

In đậm: sử dụng dấu sao `**dấu sao**` -> **dấu sao** hoặc `__dấu gạch dưới__` -> __dấu gạch dưới__.

Bạn cũng có thể kết hợp cả hai: `**dấu sao và _dấu gạch dưới_**` -> **dấu sao và _dấu gạch dưới_**.

# Trích dẫn

{% highlight bash %}
>Trích dẫn
{% endhighlight bash %}

>Trích dẫn

# Các nút bàn phím

Trong trường hợp bạn cần hiển thị một số phím tắt bàn phím, giống như `Ctrl`{: .key} + `A`{:.key} sử dụng công thức sau:

{% highlight bash %}
`Ctrl`{: .key} + `A`{:.key}
{% endhighlight bash %}