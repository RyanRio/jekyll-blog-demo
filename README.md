# Jekyll Blog Demo
> A minimal static site blog based on a Jekyll sample

This project demonstrates how to build a static site with a few pieces of content template files which are built into full webpages with more structure and style. The content files are markdown and HTML files at the top-level and some markdown post files in a subdirectory.

Most of this repo created using a base template generated by [Jekyll](https://jekyllrb.com/) as such:

```bash
$ jekyll new jekyll-blog-demo
```


## Setup and Run

This project was setup to run both locally and on Github Pages.

For instructions on how to setup and run this project locally, see my [gist](https://gist.github.com/MichaelCurrin/1085ab164550b31272699920b5549d4b).

A small detail on how this is hosted on Github Pages - since this is hosted a _Project Page_ on a _Github.io_ path and not a _User Page_ on a root, the assets are reference relative to the root domain by default. So that would give `404` errors without modification. Therefore, the empty `baseurl` in [config file](_config.yml) was replaced with a value.


## Gems

This project uses the following gems, which came with the sample blog:

- [jekyll](https://github.com/jekyll/jekyll) - This builds the site locally or in the cloud. _"Jekyll is a blog-aware static site generator in Ruby"_ 
- [minima](https://github.com/jekyll/minima) - This is a theme to add styling to built pages. _"Minima is a one-size-fits-all Jekyll theme for writers."_ 
- [jekyll-feed](https://github.com/jekyll/jekyll-feed) - Produce RSS feed. _"A Jekyll plugin to generate an Atom (RSS-like) feed of your Jekyll posts."_
