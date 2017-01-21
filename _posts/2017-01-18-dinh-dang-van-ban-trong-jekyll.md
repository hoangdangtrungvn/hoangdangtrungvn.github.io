---
layout: post
title: Định dạng văn bản trong jekyll
date: 2017-01-18 21:41:00
tags: jekyll
description: Các ví dụ về định dạng văn bản trong jekyll.
---

# Các ví dụ định dạng văn bản trong jekyll

Một số ví dụ định dạng văn bản đối với các đối tượng văn bản thông thường.

# Các tiêu đề

Trong html để định dạng tiêu đề ta dùng các thẻ <h1> đến <h6>. Trong jekyll ta sử dụng ký tự # trước nội dung tiêu đề.
Sử dụng một ký tự # tương ứng với thẻ <h1>, hai ký tự # tương ứng với thẻ <h2>. Tương tự với các thẻ <h3> đến <h6>. Tối đa là sáu ký tự #.

# Tiêu đề 1

## Tiêu đề 2

### Tiêu đề 3

#### Tiêu đề 4

##### Tiêu đề 5

###### Tiêu đề 6

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