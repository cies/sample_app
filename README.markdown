# Ruby on Rails Tutorial: Minimal Twitter clone

This is the sample application for [*Ruby on Rails Tutorial: Learn Rails by Example*](http://railstutorial.org/) by [Michael Hartl](http://michaelhartl.com/).

It has been stripped down to the bare minimum by me (Cies Breijs) in order to suit as an example of MVC for web applications.

    git clone git@github.com:cies/sample_app.git
    cd sample_app
    sudo apt-get install ruby-dev libsqlite3-dev  ;# install OS dependencies
    bundle install                                ;# install Ruby dependencies
    bundle exec rake db:migrate                   ;# setup db tables (sqlite)
    ./script/rails server                         ;# start development server

Now you can point your browser to `0.0.0.0:3000` and start micro-blogging!
