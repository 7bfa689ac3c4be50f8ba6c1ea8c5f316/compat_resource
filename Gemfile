source 'https://rubygems.org'
gem 'stove'
gem 'community_cookbook_releaser'
gem 'rack', '< 2.0' # 2.0 requires Ruby 2.2+
gem 'rspec'
gem 'rake'
if ENV['GEMFILE_MOD']
  instance_eval(ENV['GEMFILE_MOD'])
else
  gem 'chef', '~> 12.3.0'
end
