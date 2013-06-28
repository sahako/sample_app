source 'https://rubygems.org'

gem 'rails', '3.2.13'
gem 'bootstrap-sass', '2.1'
gem 'bcrypt-ruby', '3.0.1'
gem 'faker', '1.0.1'
gem 'will_paginate', '3.0.3'
gem 'bootstrap-will_paginate', '0.0.6'
gem 'jquery-rails', '2.0.2'

group :development, :test do
  gem 'sqlite3', '1.3.5'
  gem 'rspec-rails', '2.11.0'
  gem 'guard-rspec', '1.2.1'
  gem 'guard-spork', '1.2.0' 
  gem 'spork', '0.9.2'
  gem 'childprocess', '0.3.6'
  gem 'annotate', '2.5.0'

  gem 'linecache19', '0.5.13', :path => "~/.rvm/gems/ruby-1.9.3-p392/gems/linecache19-0.5.13/"
  gem 'ruby-debug-base19', '0.11.26', :path => "~/.rvm/gems/ruby-1.9.3-p392/gems/ruby-debug-base19-0.11.26/"
  gem 'ruby-debug19', :require => 'ruby-debug'

end

# assets でのみ使用され、
# デフォルトのプロダクション環境では必要のないGem
group :assets do
  gem 'sass-rails',   '3.2.5'
  gem 'coffee-rails', '3.2.2'
  gem 'uglifier', '1.2.3'
end

group :test do
  gem 'capybara', '1.1.2'
  gem 'factory_girl_rails', '4.1.0'
  gem 'cucumber-rails', '1.2.1', :require => false
  gem 'database_cleaner', '0.7.0'
  # gem 'launchy', '2.1.0'
  # gem 'rb-fsevent', '0.9.1', :require => false
  # gem 'growl', '1.0.3'
end

group :production do
  gem 'pg', '0.12.2'
end
