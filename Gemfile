source 'https://rubygems.org'

RONIN_URI  = 'https://github.com/ronin-ruby'

gemspec

gem 'jruby-openssl', '~> 0.7', :platforms => :jruby

# Ronin dependencies:
gem 'ronin-support',  '~> 0.6', git:    "#{RONIN_URI}/ronin-support.git",
                                branch: '0.6.0'

group :development do
  gem 'rake'
  gem 'kramdown'

  gem 'rubygems-tasks', '~> 0.2'
  gem 'rspec',          '~> 3.0'
end
