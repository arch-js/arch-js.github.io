# [Arch website](http://arch-js.github.io)

Documentation website for [Arch](http://arch-js.github.io).

## Installing
The Arch website is built by Jekyll using Github pages. To run the website locally you will need to install Jekyll with the Github pages gem to ensure local rendering is accurate, as described [here](https://help.github.com/articles/using-jekyll-with-pages/).

In short:
```
$ gem install bundler
$ bundle install
```

## Running
To run Jekyll in a way that matches the GitHub Pages build server, run Jekyll with Bundler. Use the command

```
$ bundle exec jekyll serve
```

and the site should be served on `http://localhost:4000`.

## Contributing
The documentation in the Arch website is kept in sync with that in the [Arch repository](http://arch-js.github.io) by [ArchBot](https://github.com/archbot). If you need to update any documentation, submit a pull request to [Arch](http://arch-js.github.io), and when the branch is merged into master ArchBot will commit the changes here after all the tests have passed.

To add a new page to the docs, create a new file in [Arch's docs folder](https://github.com/arch-js/arch/tree/master/docs). After it has been merged in, create a new entry in the `articles.yml` [data file](https://github.com/arch-js/arch-js.github.io/tree/master/_data). The position of the article in this file denotes the page number of the article in the website.
