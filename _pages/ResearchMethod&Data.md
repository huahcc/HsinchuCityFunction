---
title: "研究方法 & 資料"
excerpt_separator: "<!--more-->"
categories:
  - Research
tags:
  - DBSCAN
  - SnowNLP
permalink: /ResearchMethod&Data/
---


## 研究流程

本章節將先介紹本研究之分析流程，與其所需應用到的研究方法。


<img src="/assets/images/research_flow.png" alt="">



The preferred way of using images is placing them in the `/assets/images/` directory and referencing them with an absolute path. Prepending the filename with `{% raw %}{{ site.url }}{{ site.baseurl }}/assets/images/{% endraw %}` will make sure your images display properly in feeds and such.

Standard image with no width modifier classes applied.

**HTML:**

```html
{% raw %}<img src="{{ site.url }}{{ site.baseurl }}/assets/images/filename.jpg" alt="">{% endraw %}
```

**or Kramdown:**

```markdown
{% raw %}![alt]({{ site.url }}{{ site.baseurl }}/assets/images/filename.jpg){% endraw %}
```

![Unsplash image 9]({{ site.url }}{{ site.baseurl }}/assets/images/unsplash-image-9.jpg)

Image that fills page content container by adding the `.full` class with:

**HTML:**

```html
{% raw %}<img src="{{ site.url }}{{ site.baseurl }}/assets/images/filename.jpg" alt="" class="full">{% endraw %}
```

**or Kramdown:**

```markdown
{% raw %}![alt]({{ site.url }}{{ site.baseurl }}/assets/images/filename.jpg)
{: .full}{% endraw %}
```

![Unsplash image 10]({{ site.url }}{{ site.baseurl }}/assets/images/unsplash-image-10.jpg)
{: .full}


All children, except one, grow up. They soon know that they will grow up, and the way Wendy knew was this. One day when she was two years old she was playing in a garden, and she plucked another flower and ran with it to her mother. I suppose she must have looked rather delightful, for Mrs. Darling put her hand to her heart and cried, "Oh, why can't you remain like this for ever!" This was all that passed between them on the subject, but henceforth Wendy knew that she must grow up. You always know after you are two. Two is the beginning of the end.

Mrs. Darling first heard of Peter when she was tidying up her children's minds. It is the nightly custom of every good mother after her children are asleep to rummage in their minds and put things straight for next morning, repacking into their proper places the many articles that have wandered during the day.

<!--more-->


```yaml
excerpt_separator: "<!--more-->"
```