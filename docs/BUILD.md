# Local deployment

These instructions were tested with Ruby v3.2.3 and Bundler v2.5.11.

```shell
# Install dependencies
bundle install

# Run website locally
bundle exec jekyll serve
```

# Troubleshooting

If during

```shell
bundle install
```

you receive an error message 

```shell
Bundler::GemNotFound: Could not find csv-3.3.4.gem for installation
…
An error occurred while installing csv (3.3.4), and Bundler cannot continue.
```

you can run

```shell
gem install csv -v 3.3.4 --source https://rubygems.org/
```

to force the installation and then move forward with 

```shell
bundle exec jekyll serve
```
