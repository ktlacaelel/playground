
source 'https://rubygems.org'

# Preload the gems.
gem 'net-ssh', '2.6.5'
gem "fog-openstack" ,"0.1.24"
gem "fog-xenserver", "0.3.0"
gem 'daemons', '1.2.6'
gem 'hitimes', '1.3.0'

# Invasion
gem 'arrow', '0.0.1', :git => 'git@github.com:freshout-dev/arrow.git'
gem 'abstract_command', '0.0.6'
gem 'experimental_method', '0.0.2'
gem 'lupe', '0.0.1'

gem 'rails', '3.2.22.5'
gem 'mysql2', '0.3.20'
gem 'rack-cache', '1.2'
gem "rake", "10.1.1"
gem 'filelock', '1.1.1'
gem 'rest-client', '1.8.0'
gem '3scale_client', '2.6.1'
# gem 'jwt', '1.5.6'
gem 'algoliasearch-rails', '1.20.0'
gem 'dogapi', '1.24.0'
gem 'keen', '0.9.7'
gem 'scout_apm', '~> 3.0.x'
gem 'carrierwave_backgrounder', '0.4.2'
gem 'carrierwave_direct', '0.0.15'
gem 'simple_segment', '0.3.0'
gem 'canonical-rails', '~> 0.1.0'


group :assets do
  gem 'sass', '3.2.19'
  gem 'sass-rails',   '3.2.6'
  gem 'compass-rails','1.0.3'
  gem 'coffee-rails', '~> 3.2.1'
  gem 'uglifier', '2.7.1'
  gem 'turbo-sprockets-rails3', '0.3.14'
end

gem 'acts_as_list', '0.1.9'
gem 'jquery-rails', '3.0.4'
gem "therubyracer", '>= 0.12.0'
gem 'delayed_job_active_record', '4.1.1'
gem 'airbrake', '4.0.0'
gem "mini_magick", "3.7.0"
gem "aws-s3", '0.6.3'
gem 'whenever', '0.8.4', :require => false
gem 'carrierwave', '0.9.0'
gem 'bcrypt-ruby', '~> 3.0.0'
gem 'nokogiri', '~> 1.6.0'
gem "will_paginate", "~> 3.0.pre2"
gem 'jpbuilder', '0.2.2'
gem 'fog', '1.41.0'
gem 'acts-as-taggable-on', '3.5.0'
gem 'recurly', '2.17.0'
gem 'sendgrid-ruby', '1.1.6'
gem 'sendgrid_toolkit', '>= 1.1.1'
# gem 'postmark-rails', '~> 0.5.2'
gem "active_model_serializers", "0.8.1"
gem "createsend", "~> 3.4.0"
gem "friendly_id", "~> 4.0.10"
gem 'sitemap_generator', "5.0.5"
gem "jquery-fileupload-rails", "0.4.1"
gem 'unf', "0.1.4"
gem "httparty", "0.13.1"
gem 'addressable', "2.3.6"
gem 'zipruby', "0.3.6"
gem 'image_sorcery', "1.1.0"
gem "raindrops", "0.12.0"
gem 'kgio', "2.8.1"
gem "streamio-ffmpeg", "1.0.0"
gem 'rack-utf8_sanitizer', "1.2.4"
gem 'google-api-client', '0.8.2'
gem 'le', '2.7.1'
gem 'ddtrace', '0.24.0'
gem "asset_sync", '2.0.0'
gem "cocoon", '1.2.5'
gem "vero", '0.9.1'
gem "timers", '4.1.2'
gem 'pry',"~> 0.10.4"

group :staging, :production do
  gem 'unicorn', '4.6.3'
  # Gems for the algolia Query Suggestions tool
  gem 'damerau-levenshtein', '1.3.0'
  gem 'parallel', '~> 1.12.0'
end

group :development do
  gem 'sinatra'
  gem 'quiet_assets', "1.0.2"
  gem "nifty-generators"
  gem "byebug", '9.0.6'
  gem 'letter_opener', "1.1.2"
  gem 'webrick', '~> 1.3.1'
  gem 'rails-dev-tweaks', '~> 1.1'
end

group :test do
  gem "capybara", "~> 2.1.0"
  gem "poltergeist", "~> 1.4.1"
  gem "database_cleaner", "~> 1.2.0"
end

# ORLANDO: this is here cuz we want generators
group :development, :test do
  gem "rspec-rails", "~> 2.14.0"
  gem 'railroady'
  gem "factory_girl_rails", "~> 4.2.1"
  # gem "pry-debugger", "~> 0.2.2"
end

gem "mocha", :group => :test
gem 'throttling'

# Support for Source Maps generation
gem 'uglifier_with_source_maps', '~> 1.0.4', :git => 'git@github.com:freshout-dev/uglifier_with_source_maps.git'

gem 'sso_client', :git => 'git@github.com:envato/sso-client.git'
