# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* bundle install
* rake db:migrate
* rails s

RAILS_ENV=production rake secret
RAILS_ENV=production rake db:migrate
RAILS_ENV=production rake assets:precompile
\config\environments\production.rb ... config.assets.compile = true
RAILS_ENV=production rails s