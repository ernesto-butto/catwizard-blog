# catwizard-blog

Blog site: https://github.com/mmistakes/so-simple-theme#installation

Install ruby, in mac do `brew install ruby`

Install jekyll: https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/

Then `bundle install` to download the libraries in the `Gemfile`

Run locally with `bundle exec jekyll serve`

Added custom domain using the A records method here: https://help.github.com/articles/setting-up-an-apex-domain/

To start on server go to

`development@Oroku:~/production/catwBlog/catwizard-blog/_site$ screen -L -S blog http-server -p 8031`

Los autores estan en `_data/authors`

Favicon agregado en `_includes/head-custom.html`, ver https://github.com/mmistakes/so-simple-theme#overriding-includes-and-layouts
