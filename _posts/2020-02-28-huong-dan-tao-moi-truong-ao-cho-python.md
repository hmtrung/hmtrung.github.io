---
layout: post
title: Hướng dẫn tạo môi trường ảo cho Python
# subtitle: Each post also has a subtitle
gh-repo: daattali/beautiful-jekyll
gh-badge: [star, fork, follow]
tags: [python]
comments: true
---

1. Mở terminal, sau đó change directory đến thư mục chứa project:

~~~
$ cd my-project
~~~

2. Tạo môi trường ảo, đặt tên là "venv":

~~~
$ virtualenv venv
~~~

3. Vẫn đứng ở thư mục hiện tại, tiến hành kích hoạt môi trường ảo:

~~~
$ venv\Scripts\activate
~~~

4. Make sure file requirements.txt tồn tại trong thư mục gốc của project, tiến hành cài đặt các gói cần thiết:

~~~
$ pip install -r requirements.txt
~~~

5. Sau khi cài đặt xong, kiểm tra lại version của python, và các gói vừa cài đặt:

~~~
$ python --version
$ pip freeze
~~~
