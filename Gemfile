source 'https://rubygems.org'

ruby '2.5.7'
gem 'actionmailer', '~> 6.0', '>= 6.0.3.5'
gem 'compass-rails', '>= 4.0.0'
gem 'faraday-http-cache', '~> 2.0'
gem 'figaro'
gem 'font-awesome-rails', '>= 4.7.0.5'
gem 'google-api-client', '~> 0.9'
gem 'haml-rails', '>= 2.0.1'
gem 'kaminari-actionview', '=1.1.1'
gem 'kaminari-core', '=1.1.1'
gem 'ohanakapa', '~> 1.1.1'
gem 'puma'
gem 'rack-rewrite', '~> 1.5.0'
gem 'railties', '~> 6.0', '>= 6.0.3.5'
gem 'recaptcha'
gem 'redis-rack-cache', git: 'https://github.com/monfresh/redis-rack-cache.git', branch: 'readthis-compatibility'
gem 'sass-rails', '~> 5.0.8'
gem 'skylight'
gem 'sprockets', '~> 3.7.1'
gem 'uglifier'
gem 'webpacker', '~> 4.2', '>= 4.2.2'

# dev and debugging tools
group :development do
  gem 'better_errors'
  gem 'binding_of_caller', platforms: %i[mri_19 rbx]
  gem 'bummr'
  gem 'derailed'
  gem 'flamegraph'
  gem 'letter_opener'
  gem 'rack-mini-profiler', require: false
  gem 'reek'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'spring-watcher-listen'
  gem 'stackprof'
  gem 'yard'
end

group :test do
  gem 'capybara'
  gem 'email_spec'
  gem 'haml_lint'
  gem 'rails-controller-testing', '>= 1.0.5'
  gem 'rubocop'
  gem 'rubocop-rails'
  gem 'simplecov', '=0.17.1', require: false
  gem 'vcr'
  gem 'webdrivers', '>= 4.1.2'
  gem 'webmock', '~> 3.4'
end

group :development, :test do
  gem 'rspec-rails', '~> 3.9', '>= 3.9.1'
end
