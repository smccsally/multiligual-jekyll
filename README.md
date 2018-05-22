# Multilingual-treat-jekyll-template

This is a fork from treat-jekyll-template of [CloudCannon](http://cloudcannon.com/) 

Multilingual Food/baking blog template for Jekyll. Browse through a [live demo](https://salichen.com/multiligual-jekyll/).

You can follow [ISO language codes](https://en.wikipedia.org/wiki/List_of_ISO_639-1_codes) for language setting.

# Setup

1. Add your site details and change pagination setting in `_config.yml`.
2. Add `lang:`  and `ref:` in front matter for the pages and post that are multilingual.
   * `ref:` : assign the pages to the same ref value e.g. `/zh/index.html` and `/index.html` both have `ref: index` in front matter.
2. Add you second language pages to root directory e.g. `/zh`
3. Add your second language posts to e.g. `_posts/zh` .
4. Add your details to `_data/sidebar.yml`
5. Add your details to `_data/navigation.yml`
6. Get a workflow going to see your site's output (with Jekyll locally).

## Create a cooking blog multilingual website from scratch

1. Have a look at the template [treat-jekyll-template](https://github.com/CloudCannon/treat-jekyll-template), which explains how the template works.
2. Clone the repo: `git clone https://github.com/smccsally/treat-jekyll-template-multilingual.git`
3. Open the folder: `cd treat-jekyll-template-multilingual`
4. Remove `Readme.md` which is useless outside this repository
5. Build the website: `jekyll build`
6. Upload only the `_site` folder to github pages as [this instruction](https://stackoverflow.com/questions/28249255/how-do-i-configure-github-to-use-non-supported-jekyll-site-plugins/28252200#28252200)

P.S. github does not allow jekyll-multiple plugin so the site need to build locally and be uplaoded. 
## Features

* multilingual pagination
* multilingual posts
* multilingual pages
* customised SEO script for posts

