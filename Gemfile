source 'https://rubygems.org'

# For heroku
ruby '1.9.3'

gem 'rails',    '3.2.12'
gem 'sidekiq',  '~> 2.7.5'

# Turns every field on a editable one
gem 'best_in_place'


# State machine for attributes on models
gem 'state_machine', require: 'state_machine/core'

# Database and data related
gem 'pg'
gem 'pg_search'
gem 'postgres-copy'
gem 'schema_plus'
gem 'schema_associations'

# Payment engine using Paypal
gem 'catarse_paypal_express', git: 'git://github.com/devton/catarse_paypal_express.git',  ref: '020e5851f8c2b08c9e4c1f4aab3627414644876b'

# Payment engine using Moip
gem 'catarse_moip',           git: 'git://github.com/devton/catarse_moip.git',            ref: 'd71157a0365611048a36180846a3c0c84768b916'

# TODO: Check the Catarse_Moip dependency
gem 'moip', '2.1.2'


# Decorators
gem 'draper'

# Frontend stuff
gem 'slim'
gem 'slim-rails'
gem 'jquery-rails'
gem 'initjs'

# Authentication and Authorization
gem 'omniauth'
gem 'omniauth-twitter'
gem 'omniauth-facebook', '1.4.0'
gem 'devise'

# See https://github.com/ryanb/cancan/tree/2.0 for help about this
# In resume: this version of cancan allow checking for authorization on specific fields on the model
gem 'cancan', git: 'git://github.com/ryanb/cancan.git', branch: '2.0', ref: 'f1cebde51a87be149b4970a3287826bb63c0ac0b'


# Error reporting
gem "airbrake"

# Email marketing using mailchimp
gem 'catarse_mailchimp', git: 'git://github.com/devton/catarse_mailchimp'

# HTML manipulation and formatting
gem 'formtastic',   '~> 2.1.1'
gem "auto_html",    '= 1.4.2'
gem 'kaminari'

# Uploads
gem 'carrierwave', '~> 0.7.0'
gem 'rmagick'
gem 'fog'

# Other Tools
gem 'feedzirra'
gem 'validation_reflection',      git: 'git://github.com/ncri/validation_reflection.git'
gem 'inherited_resources',        '1.3.1'
gem 'has_scope'
gem 'spectator-validates_email',  require: 'validates_email'
gem 'has_vimeo_video',            '~> 0.0.5'
gem 'enumerate_it'
gem 'httparty', '~> 0.8.1'

# Translations
gem 'http_accept_language'
gem 'routing-filter'

# Payment
gem 'activemerchant', '1.17.0', require: 'active_merchant'
gem 'httpclient',     '2.2.5'

# Server
gem 'thin'

group :development do
  gem 'mailcatcher'
  gem 'foreman'
end

group :test, :development do
  gem 'rspec-rails'
end

group :test do
  gem 'launchy'
  gem 'database_cleaner'
  gem 'mocha',      '~> 0.10.4'
  gem 'shoulda'
  gem 'factory_girl_rails'
  gem 'capybara',   '~> 2.0.2'
end


group :assets do
  gem 'sass-rails',         '~> 3.2.5'
  gem 'coffee-rails',       '~> 3.2.2'
  gem "compass-rails",      '~> 1.0.2'
  gem 'uglifier',           '~> 1.0.3'
  gem 'compass-960-plugin', '~> 0.10.4'
end



# FIXME: Not-anymore-on-development
# Gems that are with 1 or more years on the vacuum
gem 'weekdays'
gem "rack-timeout"

# TODO: Take a look on dependencies. Why not auto_html?
gem 'rails_autolink', '~> 1.0.7'

# TODO: Take a look on dependencies
gem "RedCloth"
