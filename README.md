
## Setup

1. Install blogdown
    - Pandoc [dependency](https://bookdown.org/yihui/blogdown/installation.html) fulfilled by RStudio IDE
    ```
    > install.packages( "blogdown" )
    ```
1. Clone repositories 
    - These two repositories need to be in the same parent directory (e.g. `~/git`) as we've [configured blogdown](https://bookdown.org/yihui/blogdown/github-pages.html) to save the rendered `website` in `practicalgenomics.github.io`
    ```
    $ cd ~/git
    $ git clone https://github.com/practicalgenomics/website.git
    $ git clone https://github.com/practicalgenomics/practicalgenomics.github.io
    ```

## Workflow

Preview with LiveReload

```
> setwd( "~/git/website" )
> blogdown::serve_site()
```