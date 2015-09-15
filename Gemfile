require 'json'
require 'open-uri'

# Bring in a hash of the currently standard GitHub Pages version from thier
# authoritiative list for comparison against the local environment.
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

source 'https://rubygems.org'

ruby versions['ruby']

gem 'github-pages', versions['github-pages']
