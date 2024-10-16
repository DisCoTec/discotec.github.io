# Local deployment

These instructions were tested with Ruby v3.2.3 and Bundler v2.5.11.

```shell
# Create configuration file from template
cp Gemfile.dev Gemfile

# Install dependencies
bundle install

# Run website locally
bundle exec jekyll serve
```