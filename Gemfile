ruby '1.9.3'

source 'https://rubygems.org'

gem 'travis-support',  github: 'travis-ci/travis-support'
gem 'travis-core',     github: 'travis-ci/travis-core'
gem 'travis-sidekiqs', github: 'travis-ci/travis-sidekiqs', require: nil, ref: 'cde9741'
gem 'sinatra',         github: 'sinatra/sinatra'
gem 'sinatra-contrib', github: 'sinatra/sinatra-contrib', require: nil

gem 'travis-api', github: "travis-ci/travis-api"
gem 'travis-sso', github: "travis-ci/travis-sso"

gem 'simple_states'

gem 'unicorn'
gem "sentry-raven",    github: 'getsentry/raven-ruby'
gem 'yard-sinatra',    github: 'rkh/yard-sinatra'
gem 'rack-contrib',    github: 'rack/rack-contrib'
gem 'rack-cache',      '~> 1.2'
gem 'gh',              github: 'rkh/gh'
gem 'bunny'
gem 'dalli'
gem 'pry'
gem 'metriks',        '0.9.9.2'

group :test do
  gem 'rspec',        '~> 2.11'
  gem 'factory_girl', '~> 2.4.0'
  gem 'mocha',        '~> 0.12'
  gem 'database_cleaner', '~> 0.8.0'
end

group :development do
  gem 'foreman'
  gem 'rerun'
  gem 'debugger'
end

group :development, :test do
  gem 'rake', '~> 0.9.2'
  gem 'micro_migrations', git: 'http://gist.github.com/4269321.git'
end

group :test do
  gem 'flexmock'
end

