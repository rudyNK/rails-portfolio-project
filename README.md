# Ruby on Rails Tutorial sample application

This is the sample application for
[*Ruby on Rails Tutorial:
Learn Web Development with Rails*](https://www.railstutorial.org/)
by [Michael Hartl](http://www.michaelhartl.com/).

## License

All source code in my github account:
https://github.com/rudyNK/rails-portfolio-project/tree/master/rails-portfolio-project

## Getting started

To get started with the app, clone the repo and then install the needed gems:

$ bundle install --without production

Next, migrate the database:

$ rails db:migrate

Finally, run the test suite to verify that everything is working correctly:

$ rails test

If the test suite passes, you'll be ready to run the app in a local server:

$ rails server