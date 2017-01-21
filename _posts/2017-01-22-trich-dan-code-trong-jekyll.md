---
layout: post
title: Trích dẫn code trong jekyll
date: 2017-01-22 20:45:00
tags: [code, jekyll]
description: Hướng dẫn trích dẫn code có hiển thị số dòng hoặc không hiển thị số dòng trong jekyll.
---

# Hướng dẫn trích dẫn code

Để trích dẫn code ta sử dụng: `{{ "{%" }} highlight tên_ngôn_ngữ %}`.

Ví dụng với mã JSON: `{{ "{%" }} highlight json %}`.
{% highlight json %}
{"employees":[
    {"hoTen":"Hoàng Đăng Trung", "ngaySinh":"05/03/1994"},
    {"hoTen":"Hoàng Gia Khiêm", "ngaySinh":"23/09/2006"},
    {"hoTen":"Vũ Hồng Oanh", "ngaySinh":"03/10/1995"}
]}
{% endhighlight json %}

Hiển thị số dòng sử dụng: `{{ "{%" }} highlight tên_ngôn_ngữ linenos %}`.
{% highlight json linenos %}
{"employees":[
    {"hoTen":"Hoàng Đăng Trung", "ngaySinh":"05/03/1994"},
    {"hoTen":"Hoàng Gia Khiêm", "ngaySinh":"23/09/2006"},
    {"hoTen":"Vũ Hồng Oanh", "ngaySinh":"03/10/1995"}
]}
{% endhighlight json %}