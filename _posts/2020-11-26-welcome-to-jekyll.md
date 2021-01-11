---
layout: post
title: Project One
cover: cover.jpg
date:   2013-12-09 12:00:00
categories: posts
---

{% assign page = site.posts.first %}
{% assign content = page.content %}

About
===================

Physicist and Software Developer
-------------------

Austr. 44 / Rum / Innsbruck / Austria

"Man muss die Dinge so einfach wie möglich machen. Aber nicht einfacher!"  
(A. Einstein)

```c
// return the count of children of `head`
int count(node_t* head)
{
    if (head == NULL)
        return 0;

    return 1 + count(head->left) + count(head->right);
}
```

And here come the projects
========================


[awesome!]()

And here comes the next project
------------------------


![showcase]({{ 'images/showcase.gif' | absolute_path }})

