# DSA LSC

To get started editing the DSA LSC website:

```
1. git clone git@github.com:tadiou/dsa-lsc.git
2. cd dsa-lsc
3. bundle install
4. bower install
5. bundle exec middleman
```

DSA LSC uses middleman-foundation-6.

middleman-foundation-6 is a minimal [Middleman](http://middlemanapp.com/) project template using the [SASS](http://sass-lang.com) version of the [ZURB Foundation](http://foundation.zurb.com) framework, version 6.

Lots of this is based on [middleman-zurb-foundation](https://github.com/axyz/middleman-zurb-foundation) by [axyz](http://twitter.com/axyz); thanks!

## Prerequisites

1. ruby (2.4.0)
1. middleman ($ `gem install middleman`)
1. bower ($ `npm install -g bower`)
1. git

## Installing middleman-foundation-6 as a Middleman Template

1. $ `middleman init my_new_project --template=paperdigits/middleman-foundation-6`
1. $ `cd my_new_project`
1. $ `bower install`
1. $ `bundle exec middleman`

You'll probably want to grab the latest `_settings.scss` [from the Foundation github page](https://raw.githubusercontent.com/zurb/foundation-sites/master/scss/settings/_settings.scss) and import it into the stylesheet.

Now you can start hacking on `source` directory and watch live changes on [localhost:4567](http://localhost:4567).

For more help follow [Middleman's project template instructions](https://middlemanapp.com/advanced/project_templates/).
