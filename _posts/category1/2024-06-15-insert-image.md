---
title: 004. Insert Image
tags:
  - jekyll ubuntu
  - sample post
categories:
  - category1
  - sub category1
---

You can insert image on your markdown post file.

1. create a folder at

{% highlight ruby %}
# /assets/imgs/{category_name}/{sub_category_name}/{filename_without_date_and_extendsion}
{% endhighlight %}

2. Put the image files on created folder.

3. call the image on your markdown file.

Ruby plugin make all post to see the img folders you created.

{% highlight ruby %}
# variable 'page.img_folder' => /assets/imgs/{category_name}/{sub_category_name}/{filename_without_date_and_extendsion}
{% endhighlight %}

so, just call the image like below.

{% highlight ruby %}
# ![img.png] ({{ page.img_folder }}/img_filename.img_extension )
{% endhighlight %}