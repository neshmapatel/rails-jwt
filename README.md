# README

This is a simple rails api application in which jwt gem is used for providing authenticatio.

To use this ruby gem;
gem 'jwt' is typed in Gemfile and then from cmd run bundle install.

Also to provide authentication bcyrpt gem is used.
to install this gem, type
gem 'bcyrpt' or it might be there in your gemfile but is commented. So remove the comment and run bundle install from cmd.

User model is crested which is having attributes as follow;

username as string
name as string
email as string
password_digest as string

Create json_web_token.rb file in lib directory.

This file contains encoding and decoding methods to encode and decode the token.
