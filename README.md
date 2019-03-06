# helmit




## Installation

Add this line to your Jekyll site's `Gemfile`:

```ruby
gem "helmit"
```

And add this line to your Jekyll site's `_config.yml`:

```yaml
theme: helmit
```

And then execute:

    $ bundle

Or install it yourself as:

    $ gem install helmit

## Usage

Make some changes to make the content more you.

- Start by configuring the site! Go to `_config.yml` and fill in as necessary.
- Edit the content in `index.html` for the blurbs on the front page.
- Revise the copyright notice in `_includes/footer.html` to take ownership! Maybe use a [Creative Commons](https://creativecommons.org/) if you're feeling generous.
- Put your content into the site! Remember to put a datestamp at the start of the filename for stuff in `_posts`. The sample content can give an example of how it works.
- Change the site's style -- `_sass/variables.scss` lets you mingle with the colors and fonts.
- The site is configured to be used as a personal site that features *blog posts* and *project posts* in two separate sections. If you have additional categories to add, then make another page in the root directory with `yourcategoryname.html` as the filename; you can just copy and paste content from `blog.html` and replace the word 'blog' with your category's name. Done.

## Contributing

Bug reports and pull requests are welcome [on GitHub](https://github.com/matildepark/helmit-jekyll-theme).

## Development

To set up your environment to develop this theme, run `bundle install`.

Your theme is setup just like a normal Jekyll site! To test your theme, run `bundle exec jekyll serve` and open your browser at `http://localhost:4000`. This starts a Jekyll server using your theme. Add pages, documents, data, etc. like normal to test your theme's contents. As you make modifications to your theme and to your content, your site will regenerate and you should see the changes in the browser after a refresh, just like normal.

When your theme is released, only the files in `_layouts`, `_includes`, `_sass` and `assets` tracked with Git will be bundled.
To add a custom directory to your theme-gem, please edit the regexp in `helmit.gemspec` accordingly.

## License

The theme is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
