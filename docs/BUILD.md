# Local deployment

You can deploy [the website locally](https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/testing-your-github-pages-site-locally-with-jekyll) to test it.

In short:

- [Install Jekyll](https://jekyllrb.com/docs/installation/),
- Clone this repository, enter it,
- Run

    ```shell
    gem install bundler jekyll
    bundle install
    bundle exec jekyll serve
    ```
- Navigate to <http://127.0.0.1:4000/>, or whichever URL is given in the terminal output.
    
If you want a fresh start, try

```console
bundle clean --force
```

and re-execute the commands above.

These instructions were tested with Ruby v3.2.3 and v3.3.8 and Bundler v2.5.10 and v2.5.11.


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



