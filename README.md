# Heroku ready, Middleman 3 with Zurb's Foundation 5 Template #

heroku-middleman-foundation5 a minimal [Middleman](http://middlemanapp.com/) project template with the [SASS](http://sass-lang.com/) version of the [ZURB Foundation 5](http://foundation.zurb.com/sites/docs/v/5.5.3/index.html) Framework.  It is Heroku deployment ready.

## Installation ##

Make sure to have:

1. ruby
1. git
1. node
1. bower ($ `npm install -g bower`)


Clone this reposistory into a working directory.

1. $ `git clone git://github.com/pcincalifornia/heroku-middleman-foundation5`

From within the working repository directory `heroku-middleman-foundation5`, run local builds.

1. $ `cd 'heroku-middleman-foundation5`
1. $ `bower install` - intalls bower components.
1. $ `bundle install` - installs gem requirements, including Middleman.
1. $ `bundle exec middleman` - launches the Middleman developmet server.
1. $ `bundle exec middleman build` - build static stie locally, optional. 
1. $ `git push` - push to GitHub.
1. $ `git push heroku` - deploy to Heroku. Middleman will build static files on Heroku servers per the `Rake` file command.

Now you can start working within the `source` directory and watch live changes on [localhost:4567](http://localhost:4567).

For more help visit [Middleman's project template instructions](http://middlemanapp.com/getting-started/welcome/).

##


#### Special thanks to [Axyz](https://github.com/axyz/) for forking from the original template [middleman-zurb-foundation](https://github.com/axyz/middleman-zurb-foundation).

## ZURB Foundation License ##

Copyright (c) 2011 ZURB, http://www.zurb.com/

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.