# Hydejack Starter Kit

A quicker, cleaner way to get started blogging with [Hydejack](https://hydejack.com/).

## Quick Start
### Running locally
1. Clone repository (git users), or [download] and unzip.
2. Open terminal, `cd` into root directory (where `_config.yml` is located)
3. Run `bundle install` [^1]
4. Run `bundle exec jekyll serve`
5. Open <http://localhost:4000/hydejack-starter-kit/>

## What's next?
* Open files and read the comments
* Read the [docs](https://hydejack.com/docs/)
* Buy the [PRO version](https://hydejack.com/download/) to get the project and resume layout, newsletter subscription box, custom forms, and more.

[^1]: Requires Bundler. Install with `gem install bundler`.

[download]: https://github.com/hydecorp/hydejack-starter-kit/archive/master.zip

# Addendum
by: Akbar Rizqiansyah

The easiest way to get this to work in github pages:
1. Clone the repo
1. Go to `_config.yml`, comment the line `theme: jekyll-theme-hydejack` and uncomment `remote_theme: hydecorp/hydejack@v9`
1. Push
1. Set the github pages

Idk, if you still need to do the `bundle install` or not. 
