# catwizard-blog

Blog site: https://github.com/mmistakes/so-simple-theme#installation

Install ruby, in mac do `brew install ruby`

Install jekyll: https://help.github.com/articles/setting-up-your-github-pages-site-locally-with-jekyll/

Then `bundle install` to download the libraries in the `Gemfile`

Run locally with `bundle exec jekyll serve`

Added custom domain using the A records method here: https://help.github.com/articles/setting-up-an-apex-domain/

To start on server go to server and run

`blogServerStart`. This runs the following alias in the server:

`alias blogServerStart='docker run -it --restart always -d --name blog_catwizard -p 8031:8080 -v /home/development/production/catwBlog/catwizard-blog/_site:/public danjellz/http-s`

Los autores estan en `_data/authors`

Favicon agregado en `_includes/head-custom.html`, ver https://github.com/mmistakes/so-simple-theme#overriding-includes-and-layouts

## Customizar
Al instalar un theme, se instala un `gem` que es una libreria en la compu. Esto es para que se pueda actualizar facilmente con `bundle update jekyll-theme-so-simple`

`open $(bundle show jekyll-theme-so-simple)`

## Overriding theme defaults

To replace layouts or includes in your theme, make a copy in your _layouts or _includes directory of the specific file you wish to modify, or create the file from scratch giving it the same name as the file you wish to override.

For example, if your selected theme has a `page` layout, you can override the theme’s layout by creating your own `page` layout in the `_layouts` directory (that is, `_layouts/page.html`).