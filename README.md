## Introduction

This is a blog engine & blog contents of <http://fermium.co> based on [jekyllbootstrap](http://jekyllbootstrap.com) & [Git Hub pages](https://pages.github.com).

## Contribution

**How can I add new post?**

Fork us first.

Blog posts are Markdown .md files. Take a look at <https://stackedit.io/editor>, a sample Markdown editor.

In _posts folder, create a folder named as your GitHub user name.

You can use any other name if you prefer not to use your Git Hub user name, but it should not be a user name of other Git Hub user. 

Then create a .md file inside your folder with following naming format:

**YEAR-MONTH-DAY-NAME.md**

For example: 2015-08-23-jspm.md

Start your file with following contents:

```code
---
layout: post
category : YOUR_BLOG_POST_CATEGORY
tagline: "YOUR_TAG_LINE(TITLE)"
tags : [TAG_ONE, TAG_TWO]
---
{% include JB/setup %}
```

Then write anything you want in Markdown format.

Send us a Pull Request!

We appreciate your contributions. 

## License

[MIT](http://opensource.org/licenses/MIT)
