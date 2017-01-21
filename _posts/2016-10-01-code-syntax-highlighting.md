---
layout: post
title: Trích dẫn code trong jekyll
date: 2016-10-01 16:25:06
tags: [code, jekyll]
description: Sample post showing how code samples would look like
---

# Hướng dẫn trích dẫn code

Để trích dẫn code ta sử dụng: `{{ "{%" }} highlight tên_ngôn_ngữ %}`.
Ví dụng với mã JSON:
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