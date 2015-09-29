## Introduction

This is a blog engine & blog contents of <http://fermium.co> based on [jekyllbootstrap](http://jekyllbootstrap.com) & [Git Hub pages](https://pages.github.com).

## Contribution

**How can I add new post?**

Fork us first.

Blog posts are Markdown .md files. Take a look at <https://stackedit.io/editor>, a sample Markdown editor.

In _posts folder, create a folder named as your GitHub user name.

You can use any other name if you prefer not to use your Git Hub user name, but it should not be a user name of other Git Hub user. 

Then create a .md file inside your folder with following naming format:

YEAR-MONTH-DAY-NAME.md

For example: 2015-08-23-jspm.md

Start your file with following contents:

```md
---
layout: post
category : YOUR_BLOG_POST_CATEGORY
tagline: "YOUR_TAG_LINE(TITLE)"
tags : [TAG_ONE, TAG_TWO]
---
{% include JB/setup %}
```

Then write anything you want in Markdown format. For example:

```md
**This text is blog, because of**
```

Send us a Pull Request!

We appreciate your contributions.

**How can I add code snippets in my blog post?** 

First create a Git Hub gist for your self at <https://gist.github.com/>

See this sample gist: <https://gist.github.com/ymoradi/10ae73088e3cbe83eb84>

Then add following markup to your post file:

{% gist 10ae73088e3cbe83eb84 %}

The code between {% gist and %} has been copied from your gist url.

[JSPM](https://raw.githubusercontent.com/Fermium-co/fermium-co.github.com/master/_posts/ymoradi/2015-08-23-jspm.md)'s markdown file is a very good sample you can take a look at taht.

## License

[MIT](http://opensource.org/licenses/MIT)
