source 'https://rubygems.org'

ruby '2.3.1'

gem 'rails',          '5.0.1'
gem 'bootstrap-sass', '3.3.6'
gem 'bcrypt',         '3.1.11'
gem 'puma',           '3.4.0'
gem 'sass-rails',     '5.0.6'
gem 'uglifier',       '3.0.0'
gem 'coffee-rails',   '4.2.1'
gem 'jquery-rails',   '4.1.1'
gem 'turbolinks',     '5.0.1'
gem 'jbuilder',       '2.4.1'
gem 'normalize-scss', '7.0.0'
gem 'scout_apm'
gem 'bootsnap',       require: false
gem 'friendly_id',    '~> 5.1.0'

group :development, :test do
  gem 'sqlite3', '1.3.12'
  gem 'awesome_print'
  gem 'byebug',  '9.0.0', platform: :mri
  gem 'rspec-rails'
  gem 'factory_girl_rails'
end

group :development do
  gem 'web-console',           '3.1.1'
  gem 'listen',                '3.0.8'
  gem 'spring',                '1.7.2'
  gem 'spring-watcher-listen', '2.0.0'
  gem 'spring-commands-rspec'
  gem 'pry-rails'
end

group :test do
  gem 'factory_girl'
  gem 'faker'
  gem 'capybara'
  gem 'guard-rspec'
  gem 'launchy'
  gem 'shoulda-matchers', git: 'https://github.com/thoughtbot/shoulda-matchers.git', branch: 'rails-5'
  gem 'rails-controller-testing'
  gem 'database_cleaner'
end

group :production do
  gem 'pg',             '0.18.4'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]