source 'https://rubygems.org'

git_source(:github) { |repo_name| "https://github.com/#{repo_name}" }

# Specify your gem's dependencies in the-idea.gemspec
gemspec

group :development, :test do
  gem 'rspec', '~> 3'
  gem 'ruby-standard', git: 'git@github.com:forward3d/ruby_standard.git', tag: 'v0.7.0'
end

group :test do
  gem 'rspec_junit_formatter', '~> 0.4', require: false
  gem 'simplecov', '~> 0.17', require: false
end
