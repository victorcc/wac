# WAC
Web Application Center

# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

get GPG key


rvm install 2.5.0
rvm use 2.5.0
rvm gemset create wac
rvm gemset use wac
gem install bundler --no-ri --no-rdoc
gem install bundler -V --no-ri --no-rdoc

* System dependencies
-RVM
-Sqlite

* Configuration

gpg --keyserver hkp://keys.gnupg.net --recv-keys 409B6B1796C275462A1703113804BB82D39DC0E3
curl -sSL https://get.rvm.io | bash -s stable
source ~/.rvm/scripts/rvm

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions
bundle exec puma
Go to
http://0.0.0.0:3000/
* ...
