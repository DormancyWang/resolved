# frozen_string_literal: true

source "https://gems.ruby-china.com"
ruby "3.2.2"

gem "puma", "~> 6.3"
gem "rack", "~> 3.0"

group :development do
  gem "rake", "~> 13.0"
end

group :development, :test do
  gem "capybara", "~> 3.39"
  gem "rack-test", "~> 2.1"
  gem "rspec", "~> 3.12"
  gem "standard", "~> 1.30"
  gem "capistrano-rbenv", "~> 2.2"
  gem "capistrano-bundler", "~> 2.0"

  gem "net-ssh", ">= 6.0.2"
  gem "ed25519", ">= 1.2", "< 2.0"
  gem "bcrypt_pbkdf", ">= 1.0", "< 2.0"
end

gem "capistrano", "~> 3.18", group: :development

gem "capistrano3-puma", "~> 6.0.0", group: :development, git: "https://github.com/DormancyWang/capistrano-puma"
