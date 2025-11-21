# Rails 7 Template

Ruby on Rails Template using Esbuild for easy Turborails interface with PostgreSQL

Be sure that all references of the original project name are changed in this files:
- app/views/layouts/application.html.erb
- config/cable.yml
- config/database.yml

# Gems
- Ruby 3.3.1
- Rails 7.1.6
- Rspec Rails 7.1.1
- Railwindcss-rails 4.4
- Redis 4.0.1
- Sidekiq 8.0.7
- Sidekiq Cron 2.3.1

# Run Application
`bin/dev`

# Run Sidekiq with Cron Jobs
`bundle exec sidekiq`

# Update manifest
`bin/rails stimulus:manifest:update`
