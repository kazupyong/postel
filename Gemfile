source 'https://rubygems.org'
source 'https://rails-assets.org'

def osx_only(require_as)
  RUBY_PLATFORM.include?('darwin') && require_as
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.1'
# Use sqlite3 as the database for Active Record
gem 'mysql2'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0', group: :doc

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

group :development, :test do
  # Access an IRB console on exception pages or by using <%= console %> in views
  gem 'web-console', '~> 2.0'

  gem 'rspec', '~> 3.0'
  gem 'rspec-rails', '~> 3.0'
  gem 'rspec-activemodel-mocks'
  gem 'generator_spec'
  gem 'spring'
  gem 'spring-commands-rspec'

  # guard
  gem 'guard-rspec'
  gem 'guard-migrate'

  # factory_girl
  gem 'factory_girl_rails'

  gem 'zipruby'

  gem 'auto_truncated_logger'

  # YARD
  gem 'yard', require: false

  # KSS
  gem 'haml'
  gem 'nkss-rails', github: 'nadarei/nkss-rails'

  # pry
  gem 'pry'
  gem 'pry-rails'
  gem 'pry-doc'
  gem 'pry-stack_explorer'
  gem 'pry-byebug'
  gem 'pry-rescue'
  gem 'pry-remote'
  gem 'pry-power_assert'

  gem 'awesome_print'
  gem 'timecop'
  gem 'tapp'

  gem 'hirb'
  gem 'hirb-unicode'

  # bullet
  gem 'bullet'

  gem 'test-queue'

  # New Relic
  gem 'newrelic_rpm'
end

group :test do

  gem 'database_cleaner'

  # Coverage
  gem 'simplecov', require: false
  gem 'simplecov-rcov', require: false

  # Report with JUnit format
  gem 'rspec_junit_formatter'

  # Notification
  gem 'rb-fsevent', require: osx_only('rb-fsevent')
  gem 'terminal-notifier-guard', require: osx_only('terminal-notifier-guard')
  gem 'test_after_commit'

  # WebAPI Test
  gem 'webmock'

  # Mail Test
  gem 'email_spec'

  gem 'capybara'
  # gem 'capybara-webkit'
  gem 'poltergeist', '~> 1.5.0', require: false
  gem 'turnip'
  gem 'accept_values_for'

  gem 'rspec-parameterized'

  # shared_context for rake tasks
  gem 'rake_shared_context'

  # HTML entity encoding and decoding
  gem 'htmlentities'

  # connection pool
  gem 'connection_pool'
end
