# Nice places

* [Geneva, Switzerland](http://olange.github.io/nice-places/geneva) _My favorite places in Geneva, to code or study_

## Contents

This repository is the source of the website [olange.github.io/nice-places](http://olange.github.io/nice-places/). New places added to the files of this repository will be automatically published to the website by [GitHub Pages](http://pages.github.com).

## Contributing

Fork this repository, add or update the places, and submit a pull request. I'd be glad to merge them and welcome updates.

See the article [Mapping geoJSON files on GitHub](https://help.github.com/articles/mapping-geojson-files-on-github) to create a map.

## Previewing changes

To preview your changes locally in a browser, you might want to [install Jekyll](https://help.github.com/articles/using-jekyll-with-pages/#installing-jekyll). Assuming you have Ruby and bundler installed:

    $ git clone git@github.com:olange/nice-places.git
    $ cd nice-places
    $ bundle install

And [let Jekyll serve](http://jekyllrb.com/docs/usage/) the site locally:

    $ bundle exec jekyll serve --watch
    Configuration file: …/nice-places/_config.yml
                Source: …/nice-places
           Destination: …/nice-places/_site
          Generating... done.
     Auto-regeneration: enabled
        Server address: http://0.0.0.0:4000
      Server running... press ctrl-c to stop.

Then point your browser to `http://localhost:4000` and start making changes. Changed files will be republished automatically by Jekyll.
