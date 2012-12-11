---
layout: default
full_title: Sculpin &mdash; PHP Static Site Generator
fancy_index: true

---

## PHP Static Site Generator

Sculpin takes plain old text files (Markdown, Textile, etc.) and combines them with Twig
templates to produce a set of static HTML files that can be easily deployed to almost any
hosting platform.


## Why Sculpin?

Sculpin is a **PHP static site generator**. If you like and are familiar with PHP, Sculpin
should be a natural fit.

Sculpin is managed by **Composer**. This may not seem like a big deal, but this means that
installing Sculpin, its dependencies, and managing the dependencies of your project are all
quite easy tasks. [Learn more about Composer](http://getcomposer.org).

Sculpin uses the **Twig template engine**. If you like Twig and want to use it as you would
expect Twig to work (including template inheritance) Sculpin is the right choice!
[Learn more about Twig](http://twig.sensiolabs.org/).

Sculpin is built around **Symfony's HTTP Kernel**. Among other things, this means that
Sculpin can leverage Symfony's Dependency Injection Container and its Bundle system.
[Learn more about Symfony Bundles](http://symfony.com/doc/2.0/cookbook/bundles/index.html).


## Community

If you have questions please make sure to check in with the Sculpin
[community]({{site.url}}/community)! Whether it be IRC, [Twitter](http://twitter.com/getsculpin),
or mailing list, we are here for you!


## Project Status

Sculpin continues to be **unstable**, under heavy development, and lacking in-depth documentation.
Be prepared for possible changes in core functionality requiring you to fix your existing
site.

If you are interested in trying out Sculpin please check out the
[documentation]({{site.url}}/documentation).


#### So Does It Actually Work?

Yes! There are several sites currently generated by Sculpin. In fact, the site you are reading
right now is generated by Sculpin.
[View its source on GitHub!](https://github.com/sculpin/getsculpin.com)