# fuyuko.net hosted on GitHub Pages

## Dependencies

* Host - [GitHub Pages](https://pages.github.com/)
* Theme - [Tactile theme](https://github.com/pages-themes/tactile) 


## Authors

Fuyuko Gratton

## Resources

* [GitHub Pages documentation](https://docs.github.com/en/pages)
* [Exploring Jekyll Basics via a Blog](https://evanwill.github.io/go-go-ghpages-b/content/3-blog.html)
* [3 Simple steps to setup Jekyll Categories and Tags](https://blog.webjeda.com/jekyll-categories/#create-a-category-page)
* [jekyllrb.com - post](https://jekyllrb.com/docs/posts/)

## Local Testing

Since Github page uses remote themes (for Tactile theme), the file structure in PROD is different when using Tactile theme. 
Hence, I can't test the local copy of this repository (missing theme file error). So instead, I test my content in the theme's clone in my local environment.

1. Clone down the theme's repository
1. `cd` into the theme's directory
1. Run script/bootstrap to install the necessary dependencies
1. Make changes in the theme's directory
1. Run `bundle exec jekyll serve` to start the preview server
Visit localhost:4000 in your browser to preview the theme
