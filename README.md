# Subcommission on Triassic Stratigraphy

A Jekyll website for the International Commission on Stratigraphy's Subcommission on Triassic Stratigraphy,
based on [subcommission-template](https://github.com/i-c-stratigraphy/subcommission-template).

The background colour is `#824FA8`, as specified in the template README.
Executive details are sourced from the
[ICS subcommissions page](https://github.com/i-c-stratigraphy/i-c-stratigraphy.github.io/blob/master/pages/subcommissions.md).

## Run locally

Use Ruby 3.4 and Bundler 2.6 or later.

```sh
bundle install
bundle exec jekyll serve
```

Open `http://localhost:4000/subcommission-triassic/`.
To build without serving, run `bundle exec jekyll build`.

## Deployment

The GitHub Actions workflow builds Jekyll and deploys to GitHub Pages on pushes to `main`.
The project URL is <https://stratigraphy.org/subcommission-triassic/>.
Set `url` and `baseurl` in `_config.yml` when moving to a custom domain.

## License

Content is licensed under [CC BY 4.0](LICENSE). Copyright International Commission on Stratigraphy.
