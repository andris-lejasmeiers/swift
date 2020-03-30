# Swift Style Guide

This is the source for the [Swift Style Guide](https://andris-lejasmeiers.github.io/swift)
website, which is based on the [Google Swift Style Guide](https://google.github.io/swift).

## Local Deployment

The website is generated using [Jekyll](https://jekyllrb.com). Follow the procedure below to deploy it locally.

1. Have a Ruby >= 2.4.0 installed. macOS Catalina 10.15 comes with ruby 2.6.3, so you’re fine.
2. Run the following commands as a regular, unprivileged user:
   1. `xcode-select --install` to install the command line tools.
   2. `gem install --user-install bundler jekyll` to install the [Bunder](https://jekyllrb.com/docs/ruby-101/#bundler) and [Jekyll](https://jekyllrb.com).
   3. `bundle install --path ~/.gem` to install the dependencies specified in `Gemfile`.
   5. `bundle exec jekyll serve`
3. Visit [http://localhost:4000/swift/](http://localhost:4000/swift/)

Notes:
* Changes to `_config.yml` require restarting the local server (step 2.5 above).
* After you make edits to the source, refresh your browser.
