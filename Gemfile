source "https://rubygems.org"


gem "rails", "~> 7.2.1"
gem "pg", "~> 1.1"
gem "puma", ">= 5.0"
gem "rswag-api"
gem "rswag-ui"



# gem "kredis"


# gem "bcrypt", "~> 3.1.7"

gem "tzinfo-data", platforms: %i[ windows jruby ]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false


# gem "image_processing", "~> 1.2"

gem "rack-cors"

group :development, :test do
  gem "brakeman", require: false
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "ffaker", "~> 2.21"
  gem "rswag-specs", "~> 2.14"
  gem "rspec-rails", "~> 7.0", ">= 7.0.1"
  gem "rubocop-rails-omakase", require: false
  gem "rubocop", "~> 1.66", ">= 1.66.1", require: false
end

group :test do
  gem "simplecov",  "~> 0.22.0",  require: false
end
