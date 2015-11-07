# coding: utf-8
if ENV['USE_OFFICIAL_GEM_SOURCE']
  source 'https://rubygems.org'
else
  source 'https://ruby.taobao.org'
end



# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~>4.2.4'
# Sprockets 是一个 Ruby 库，用来检查 JavaScript 文件的相互依赖关系，用以优化网页中引入的js文件，以避免加载不必要的js文件，加快网页访问速度。这个现在貌似是rails工程默认自带gem，记不太清了，足见重要性。但是我在使用中发现有时候会跟bootstrap的js库发生冲突，主要是版本问题，有使用的小伙伴需要注意一下。
gem 'sprockets', '~> 3.3.3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.1.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use jquery as the JavaScript library
gem 'jquery-rails', '~>4.0.4'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks', github: 'rails/turbolinks'
gem 'jquery-turbolinks'
#Rails4中已经将页面缓存和动作缓存，剥离出来了，独立成了两个Gems,要想使用这两种缓存，需要安装actionpack-page_caching,actionpack-action_caching gem。
gem 'actionpack-action_caching', '1.1.1'
#Rails应用的国际化［i18n］
gem 'rails-i18n'
#A gem which helps you detect the users preferred language, as sent by the "Accept-Language" HTTP header.
gem 'http_accept_language'
#This is an extraction of the `auto_link` method from rails. The `auto_link` method was removed from Rails in version Rails 3.1. This gem is meant to bridge the gap for people migrating.
gem 'rails_autolink', '>= 1.1.0'
#Markdown Emoji was designed to work with the Redcarpet markdown processor and Rails 3.1 with the asset pipeline enabled.
gem 'md_emoji', '1.0.2'
#The Exception Notification gem provides a set of notifiers for sending notifications when errors occur in a Rack/Rails application.
gem 'exception_notification'
#Doorkeeper is a gem that makes it easy to introduce OAuth 2 provider functionality to your Rails or Grape application.
gem 'doorkeeper'
gem 'doorkeeper-i18n', github: 'doorkeeper-gem/doorkeeper-i18n'
#This guide covers the various ways of performance testing a Ruby on Rails application.
gem 'rails-perftest'
#ruby-prof is a fast code profiler for Ruby. Its features include:
gem 'ruby-prof'

#上传组件
#This gem provides a simple and extremely flexible way to upload files from Ruby applications. It works well with Rack based web applications, such as Ruby on Rails.
gem 'carrierwave', '~> 0.10.0'
#This gem adds support for upyun.com to CarrierWave
gem 'carrierwave-upyun', '0.1.8'
#A ruby wrapper for ImageMagick or GraphicsMagick command line.
gem 'mini_magick', '3.7.0', require: false


#  Mongoid 辅助插件
gem 'mongoid', '4.0.2'
gem 'mongoid-rails'
gem 'mongoid_auto_increment_id', '0.6.4'
gem 'mongoid_rails_migrations', '1.0.0'

# 用户系统
gem 'devise', '~> 3.5.1'
gem 'devise-async'
gem 'devise-encryptable', '0.1.2'

# 分页
gem 'will_paginate', '3.0.7'

# 三方平台 OAuth 验证登陆
gem 'omniauth', '~> 1.2.2'
gem 'omniauth-github', '~> 1.1.0'

# permission
gem 'cancancan', '~> 1.8.4'

gem 'redis', '~> 3.2.1'
gem 'hiredis', '~> 0.6.0'
# Redis 命名空间
gem 'redis-namespace', '~> 1.5.1'
# 将一些数据存放入 Redis
gem 'redis-objects', '1.1.0'

# Markdown 格式 & 文本处理
gem 'redcarpet', '~> 3.3.3'
gem 'rouge', '~> 1.8.0'
gem 'auto-space', '0.0.4'
gem 'nokogiri', '1.6.5'

# YAML 配置信息
gem 'settingslogic', '~> 2.0.9'

# 队列
gem 'sidekiq'
# Sidekiq Web
gem 'sinatra', require: nil
#A reliable, robust messaging bus for Ruby processes and web clients built on Redis.
gem 'message_bus'

# 分享功能
gem 'social-share-button', '0.1.5'

# 表单
gem 'simple_form', '3.1.0'

# API
gem 'grape', '0.7.0'
gem 'active_model_serializers'
gem 'grape-active_model_serializers'

# Mailer
gem 'postmark', '0.9.15'
gem 'postmark-rails', '0.4.1'

# Dalli, kgio is for Dalli
#kgio provides non-blocking I/O methods for Ruby without raising exceptions on EAGAIN and EINPROGRESS.  It is intended for use with the Unicorn and Rainbows! Rack servers, but may be used by other applications.
gem 'kgio'
#Dalli is a high performance pure Ruby client for accessing memcached servers.
gem 'dalli', '2.7.4'
#unicorn: Rack HTTP server for fast clients and Unix
gem 'unicorn', '4.9.0'
#Run any code in parallel Processes(> use all CPUs) or Threads(> speedup blocking operations).
gem 'parallel'

# for api 跨域
gem 'rack-cors', require: 'rack/cors'
gem 'rack-utf8_sanitizer'

# Mini profiler Middleware that displays speed badge for every html page. Designed to work both in production and in development.
gem 'rack-mini-profiler', require: false

# gem 'newrelic_rpm'
# gem 'newrelic_moped'
# gem 'newrelic-grape'

gem 'oneapm_rpm'

group :development, :test do
  gem 'capistrano', '2.9.0', require: false
  gem 'capistrano-unicorn'
  gem 'rvm-capistrano', require: false
  gem 'capistrano-sidekiq'

  gem 'rubocop'
  gem 'rspec-rails', '~> 3.3'
  gem 'factory_girl_rails', '~> 4.5.0'
  gem 'database_cleaner'
  gem 'capybara', '~> 2.3.0'
  gem 'api_taster', '0.6.0'

  gem 'jasmine-rails', '~> 0.10.2'
  gem 'derailed'

  gem 'mongoid_colored_logger'
  gem 'colorize'
  gem 'letter_opener'

  gem 'puma', '~> 2.14.0'

  # Better Errors
  gem 'better_errors'
  gem 'binding_of_caller'

  gem 'tunemygc'
end
