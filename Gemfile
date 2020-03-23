source 'https://rubygems.org'
ruby '2.3.0'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.2.8'
gem 'mysql2'
gem 'unicorn'
gem 'haml-rails', '>= 0.9.0'
gem 'sass-rails', '~> 5.0', '>= 5.0.4'
gem 'uglifier', '>= 1.3.0'
gem 'turbolinks', '>= 2.5.3'

# For View
gem 'kaminari', '>= 0.16.3'
gem 'oj'

# For Image upload
gem 'carrierwave'                 , '>= 0.11.0' # Image uploader
gem 'mini_magick'                 # resizable image
gem 'fog', require: "fog/aws/storage"

# For Model and AR
gem 'active_type', '>= 0.5.0'
gem 'factory_girl_rails', '>= 4.7.0'
gem 'enum_help'
gem 'migration_comments', '>= 0.3.2'
# gem 'draper'
gem 'devise', '>= 3.5.6'
gem 'validates_email_format_of'
gem 'active_model_serializers', '>= 0.9.5' #, git: 'git@github.com:rails-api/active_model_serializers.git'
gem "faker"

# For Config
gem 'config', '>= 1.1.0'

# For deploy
gem 'bugsnag'                  , '>= 4.0.0' # bug tracking
gem 'newrelic_rpm'             # performance monitoring

group :development do
  # For Deploy
  gem 'capistrano'
  gem 'capistrano-rails', require: false
  gem 'capistrano-bundler', require: false
  gem 'capistrano-rbenv', require: false
  #gem 'capistrano-npm', require: false
  gem 'capistrano3-unicorn'

  gem 'annotate', '>= 2.6.5'
  gem 'rails-db-resetup'
  gem 'foreman'

  # For Lint
  gem 'rubocop', require: false
  gem 'scss_lint', require: false

  # For Debug
  gem 'web-console', '~> 2.3', '>= 2.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'pry'
  gem 'awesome_print'
  gem 'hirb'
  gem 'hirb-unicode'
  gem 'letter_opener'
  gem 'rack-mini-profiler'#, require: false
  gem 'bullet', '>= 5.0.0'
  gem 'quiet_assets', '>= 1.1.0'

  gem 'byebug'
  gem 'powder'

  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
end

group :test do
  gem 'rspec'
  gem 'rspec-rails', '>= 3.4.2'
  gem 'launchy'
  gem 'database_cleaner'
  gem 'capybara'
  gem 'timecop'
  gem 'poltergeist'
  gem "chromedriver-helper"
  gem "selenium-webdriver"
  gem 'shoulda-matchers', '>= 3.1.1'
  gem 'webmock'
  gem 'vcr'
  gem 'spring-commands-rspec'
  gem "codeclimate-test-reporter", ">= 0.6.0", require: nil
end


