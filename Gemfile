source "https://rubygems.org"

gem 'emeril', :group => :release

group :integration do
  gem "test-kitchen"
  gem "kitchen-vagrant"
  gem "kitchen-docker"
  gem "librarian-chef"
end

group :test do
  gem "chefspec"
  gem 'rake'
  gem "fog", :git => 'https://github.com/fog/fog.git'
  gem "foodcritic", "~> 3.0"
  gem "librarian-chef"
end
