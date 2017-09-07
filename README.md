# hkuplg.github.io
Website of the University of Hong Kong Programming Languages Group

Theme based on [plwonks](https://wonks.github.io)

## Guide to update the site

You can follow the guide here to update the website. The general procedure is to add/edit files and then push the changes to Github. The Github pages will automatically update the website once your push is accepted.

### Seminar

Create a new markdown file in [`_posts`](_posts) folder. The filename should be "date + *optional* short title (3-4 words)", e.g., `2017-07-01.md` or `2017-07-01-an-awesome-title.md`. The file template is as follows (texts inside '<>' are hints for putting the actual content):

```markdown
--- 
layout:  post 
title:   "<the title, need quotation marks>"
authors: "<the author(s), need quotation marks>"
date:    yyyy-mm-dd HH:MM:SS +0800
venue:   "<the venue, need quotation marks>"
categories: <short name of author, no quotation marks> <the year>
--- 
## Abstract

<abstract here>
```

Title, authors and venue should be wrapped by double quotation marks. But do not put any quotations marks in the entries of "categories". Jekyll, the blog engine, just doesn't like it. You can also check the existing posts for reference, e.g. [2015-02-12-object-algebras-in.md](https://github.com/hkuplg/hkuplg.github.io/blame/master/_posts/2015-02-12-object-algebras-in.md).

### Paper reading

Directly edit [`_includes/paper-reading.md`](_includes/paper-reading.md) and add new entries. The latest entry should be added at the top. The format for the entry is as follows:

```markdown
| date | leader | [paper name](paper url) |
```

An example could be

```markdown
| Sep 4, 2017 | Bruno | [The Essence of Inheritance](https://arxiv.org/abs/1601.02059) |
```
