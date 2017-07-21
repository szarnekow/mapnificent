# Mapnificent

Make sure you have an up-to-date ruby version installed.
Install [bower](http://bower.io/) and [jekyll](http://jekyllrb.com/).

    # You need node and npm
    npm install -g bower
    # You need ruby and bundler
    bundle install
    # Python dependency to come shortly!

Then get the cities data:

    git submodule init
    git submodule update

Then run:

    bower install
    bundle exec jekyll serve -w
