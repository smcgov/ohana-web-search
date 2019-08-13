source 'https://rubygems.org'

ruby '2.5.3'
gem 'actionmailer', '~> 5.2', '>= 5.2.3'
gem 'compass-rails', '>= 3.1.0'
gem 'faraday-http-cache', '~> 2.0'
gem 'figaro'
gem 'font-awesome-rails', '>= 4.7.0.5'
gem 'google-api-client', '~> 0.9'
gem 'haml-rails', '>= 2.0.1'
gem 'kaminari-actionview', '>= 1.1.1'
gem 'kaminari-core'
gem 'ohanakapa', '~> 1.1.1'
gem 'puma'
gem 'rack-rewrite', '~> 1.5.0'
gem 'railties', '~> 5.2', '>= 5.2.3'
gem 'recaptcha'
gem 'redis-rack-cache', git: 'https://github.com/monfresh/redis-rack-cache.git', branch: 'readthis-compatibility'
gem 'sass-rails', '~> 5.0.7'
gem 'skylight'
gem 'sprockets', '~> 3.7.1'
gem 'uglifier'
gem 'webpacker', '~> 4.0', '>= 4.0.7'

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
  gem 'capybara', '>= 3.27.0'
  gem 'email_spec'
  gem 'haml_lint'
  gem 'rails-controller-testing', '>= 1.0.4'
  gem 'rubocop'
  gem 'simplecov', require: false
  gem 'vcr'
  gem 'webdrivers', '>= 4.1.2'
  gem 'webmock', '~> 3.4'
end

group :development, :test do
  gem 'rspec-rails', '~> 3.8', '>= 3.8.2'
end
