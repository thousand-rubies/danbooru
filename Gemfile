source 'https://rubygems.org/'

gem 'dotenv-rails', '>= 3.0.0', :require => "dotenv/rails-now"

gem "rails", "~> 7.0", ">= 7.0.8.1"
gem "pg"
gem "simple_form", ">= 5.2.0"
gem "sanitize", ">= 6.0.1"
gem 'ruby-vips'
gem 'diff-lcs', :require => "diff/lcs/array"
gem 'bcrypt', :require => "bcrypt"
gem 'rubyzip', :require => "zip"
gem 'stripe'
gem 'aws-sdk-sqs', '~> 1'
gem 'responders', '>= 3.1.0'
gem 'dtext_rb', git: "https://github.com/danbooru/dtext_rb.git", require: "dtext"
gem 'memoist'
gem 'daemons'
gem 'oauth2'
gem 'bootsnap'
gem 'addressable'
gem 'rakismet'
gem 'recaptcha', require: "recaptcha/rails"
gem 'activemodel-serializers-xml'
gem 'webpacker', '= 6.0.0.rc.6'
gem 'rake'
gem 'redis'
gem 'builder'
# gem 'did_you_mean' # github.com/yuki24/did_you_mean/issues/117
gem 'puma'
gem 'scenic', '>= 1.7.0'
gem 'ipaddress_2'
gem 'http'
gem 'activerecord-hierarchical_query'
gem 'http-cookie', git: "https://github.com/danbooru/http-cookie"
gem 'pundit'
gem 'mail'
gem 'nokogiri', '>= 1.15.6'
gem 'view_component'
gem 'tzinfo-data'
gem 'hsluv'
gem 'google-cloud-bigquery', require: "google/cloud/bigquery"
gem 'google-cloud-storage', require: "google/cloud/storage"
gem 'ed25519'
gem 'bcrypt_pbkdf' # https://github.com/net-ssh/net-ssh/issues/565
gem 'clockwork'
gem 'puma-metrics'
gem 'puma_worker_killer'
gem "rack-timeout", require: "rack/timeout/base"
gem "parallel"
gem "ffi"
gem "rbtrace"
gem "good_job", ">= 3.4.8"
gem "crass"
gem "public_suffix"
gem "elastic-apm"
gem "debug"
gem "ffaker"
gem "composite_primary_keys"
gem "resolv"

group :development do
  gem 'rubocop', require: false
  gem 'rubocop-rails', '>= 2.17.0', require: false
  #gem 'meta_request'
  gem 'rack-mini-profiler', '>= 3.1.0'
  gem 'stackprof'
  gem 'flamegraph'
  gem 'memory_profiler'
  gem 'better_errors', '>= 2.10.0'
  gem 'binding_of_caller'
  gem 'benchmark-ips', require: "benchmark/ips"
  gem 'listen'
  gem 'solargraph', '>= 0.48.0'
  gem 'derailed_benchmarks'
end

group :test do
  gem "shoulda-context"
  gem "shoulda-matchers"
  gem "factory_bot"
  gem "mocha", require: "mocha/minitest"
  gem "simplecov", require: false
  gem "minitest-ci"
  gem "minitest-reporters", require: "minitest/reporters"
  gem "mock_redis"
  gem "capybara", ">= 3.38.0"
  gem "selenium-webdriver"
  gem "codecov", require: false
  gem 'stripe-ruby-mock', require: "stripe_mock"
end
