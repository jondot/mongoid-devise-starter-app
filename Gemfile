source 'http://rubygems.org'

gem 'rails', '3.0.6'
gem "bson_ext", ">= 1.3.0"
gem "mongoid", ">= 2.0.1"
gem "devise", ">= 1.3.3"
gem 'kaminari'
gem 'fabrication'
gem 'resque'
gem 'resque_mailer'
gem 'asset_packager'


#
# dev, test
#
gem "rspec-rails", ">= 2.5.0", :group => [:development, :test]
group :test do
  gem "database_cleaner", ">= 0.6.7"
  gem 'factory_girl_rails', ">= 1.1.beta1"
  gem "mongoid-rspec", ">= 1.4.1"
  gem 'timecop'
  gem 'spork', ">= 0.9.0.rc7"
end

group :development do
  gem 'ruby-prof'
  gem 'compass'
  gem "haml", ">= 3.1.alpha.50" # due to some kind of bug w.r.t compass https://github.com/jlong/serve/issues/20
  gem 'sass', '>= 3.1.0.alpha.50' # due to some kind of bug w.r.t compass https://github.com/jlong/serve/issues/20
end


