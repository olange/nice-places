# Nice places

* [Geneva, Switzerland](http://olange.github.io/nice-places/geneva) _My favorite places in Geneva, to code or study_

This repository is the source of the website [olange.github.io/nice-places](http://olange.github.io/nice-places/). Any change to the files of this repository will be automatically published to the website by [GitHub Pages](http://pages.github.com).

## Contributing new places

Fork this repository, add or update the places, and submit a pull request. I'd be glad to merge them and welcome updates.

See the article [Mapping geoJSON files on GitHub](https://help.github.com/articles/mapping-geojson-files-on-github) to create a map.

## Previewing changes

To preview your changes in a browser, you might want to [install Jekyll](http://jekyllrb.com/docs/installation/):

    $ gem install jekyll

[run it locally](http://jekyllrb.com/docs/usage/):

    $ git clone git@github.com:olange/nice-places.git
    $ cd nice-places
    $ jekyll serve --watch
    Configuration file: /Users/oliv/Sources/nice-places/_config.yml
                Source: /Users/oliv/Sources/nice-places
           Destination: /Users/oliv/Sources/nice-places/_site
          Generating... done.
     Auto-regeneration: enabled
        Server address: http://0.0.0.0:4000
      Server running... press ctrl-c to stop.

and point your browser to `http://localhost:4000`. Changed markdown files will be republished automatically.
