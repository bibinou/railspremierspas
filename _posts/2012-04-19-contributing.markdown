---
layout: default
title: Contributing
permalink: contributing
---

# Contributing

The guides site uses [jekyll](https://github.com/mojombo/jekyll) to power the site and all the documents are written using [markdown](http://daringfireball.net/projects/markdown/).

To start contributing, fork the [repository on github](https://github.com/railsgirls/railsgirls.github.com).

If you're new to Git or Github, follow the Bootcamp to [set up Git](https://help.github.com/articles/set-up-git) and learn about [forking](https://help.github.com/articles/fork-a-repo).

## Adding a Guide

1. Create a file named `YYYY-MM-DD-guide_name.markdown` inside the `_posts` directory of your fork, replacing Y, M, and D by the current Year, Month and Date.
2. In this file, you'll need to add some YAML front matter at the top of the file so it looks like this:{% highlight yaml %}
---
layout: default
title: Name of the Guide
permalink: one-word-summary
---
{% endhighlight %}
3. Commit this new guide to your git repo.
4. After you commit, push that to your fork.
5. You can now open a pull request explaining your guide. That's it!

You can follow the structure of our [Rails Girls App Tutorial](https://github.com/railsgirls/railsgirls.github.com/blob/master/_posts/2012-04-18-app.markdown).

Thanks so much for taking the time to help us make Rails Girls awesome.

## Translating the Guides

In your fork, create a [new branch](http://learn.github.com/p/branching.html) from master named `lang-XX`, replacing `XX` by your [language ISO code](http://www.loc.gov/standards/iso639-2/php/code_list.php).

Then, `checkout` your new branch and start translating !

To get the new changes from Rails Girls (new guides for example), `checkout` the master branch, and `pull` the changes. Get back on your translation branch, and `merge` the master branch into it.
You may have to resolve conflicts 

