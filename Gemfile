source "https://rubygems.org"

# As per https://github.com/envygeeks/jekyll-docker/issues/335, when serving with 4.2.X (and possible earlier)
# versions of the jekyll docker image this gem is missing, which prevents the site from being served.
gem "webrick"
# Because of the above and the fact we're now provifing a Gemfile, the gems that are available by default
# when serving are affected, so we need to explcitly declare them here.
gem "github-pages"
gem "jekyll"