# InterMine.org Site [![Built with Grunt](https://cdn.gruntjs.com/builtwith.png)](http://gruntjs.com/)

This is the landing page for InterMine powered by [Jekyll](http://jekyllrb.com/) on [GitHub Pages](http://pages.github.com/).

Any changes to this, `gh-pages`, branch will get reflected at [http://intermine.github.io/intermine.org/](http://intermine.github.io/intermine.org/).

##Quickstart

Create a new post in `_posts` and then install & build:

```bash
$ gem install jekyll
$ jekyll build
```

##Commands

###Jekyll

Install:

```bash
$ gem install jekyll
```

Watch & serve for local development:

```bash
$ jekyll serve --watch --drafts
```

Build:

```bash
$ jekyll build
```

###Bower & Grunt

Install `npm` dependencies:

```bash
$ npm install -d
```

Get vendor libraries using `Bower`:

```bash
$ bower install
```

Watch styles and scripts and build them using `Grunt`:

```bash
$ watch --color -n 1 grunt
```