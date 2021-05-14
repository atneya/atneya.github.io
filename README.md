# Personal Website

This repository holds the source-code of my personal website and blog which is statically
generated via [Jekyll](https://jekyllrb.com/). You can find more reasoning regarding the 
technical and design choices I made in one of my early [posts](https://atneya.com).

## Build

In order to build the website locally, using bundler and the included gemfile along with Jekyll
is sufficient. In particular, the command 
`bundle exec jekyll serve` is sufficient.



## Credits

The themeing of this site was forked from [Kasper](https://github.com/rosario/kasper) which was 
in-turn a port of Ghost's default theme to Jekyll.

The auto-generation of the site on Github Pages utilizes a workflow that statically generates 
the website files and pushes to the `gh-pages` branch. This workflow is found at
[Jekyll Action](https://github.com/helaili/jekyll-action).

The pagination for the main page and auto-pagination for post categories is handled by 
[Jekyll-Paginate-v2](https://github.com/sverrirs/jekyll-paginate-v2).

Modified timestamps utilize [jekyll-last-modified-at](https://github.com/gjtorikian/jekyll-last-modified-at)
to provide timestamps based on git.
