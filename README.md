# felipeleusin.com

Shamelly forked [Phil Haack's blog](http://haacked.com), going to adapt it as I go.

## Testing

[HTML::Proofer](https://github.com/gjtorikian/html-proofer) is set up to validate all links within the project.  You can run this locally to ensure that your changes are valid:

```shell
bundle install
bundle exec rake test
```