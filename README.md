# Personal Homepage

A basic personal home and blog

Built off of an initial version of a [Ruby / PHP Bootstrap project](https://github.com/StartBootstrap/startbootstrap-clean-blog-jekyll) in 2017 and really needs to be updated to something better at some point, but serves as an easy way to add Markdown based posts to a website.

## Making Changes

Most places in the codebase that are most likely to be updated are included in folders prefixed with an underscore:

- `_config.yml` - Includes basic site and build settings
- `_posts`: Folder containing MD files used to populate blog
- `_layouts`:
- `_includes`: HTML for Header, Footer and Navigation elements

## Running locally

In order to run, you'll need to have installed locally:

- Ruby 3+
- Jekyll (and related dependencies / Gems if not already installed) `gem install jekyll`
- npm

To run locally, run the following command:

`bundle exec jekyll serve --watch`
