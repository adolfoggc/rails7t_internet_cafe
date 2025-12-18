# Ruby's Internet Cafe

This is an example of an Internet Cafe App

# Gems
- Ruby 3.3.1
- Rails 7.1.6
- Rspec Rails 7.1.1
- Railwindcss-rails 4.4
- Redis 4.0.1
- Sidekiq 8.0.7
- Sidekiq Cron 2.3.1
- Devise 4.9

# Run Application
`bin/dev`

# Run Sidekiq with Cron Jobs
`bundle exec sidekiq`

# Create an Authenticable Admin/User (If needed)
`rails generate devise MODEL_NAME`

# Update manifest
`bin/rails stimulus:manifest:update`
