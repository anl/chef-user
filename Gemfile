source "https://rubygems.org"

gem 'rake'
gem 'minitest', '~> 4.7'
gem 'foodcritic', :platforms => :ruby_19

# allow CI to override the version of Chef for matrix testing
gem 'chef', (ENV['CHEF_VERSION'] || '>= 0.10.10')
