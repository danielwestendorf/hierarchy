source :rubygems

gem 'rails', '>= 3.0.2'

group :development do
  # gem 'jeweler', require: nil
  # gem 'yard', require: nil
  # gem 'RedCloth', require: nil
  gem 'rspec'

  # Use platform specific gems
  platforms :ruby do
    gem 'pg'
  end

  platforms :jruby do
    gem 'activerecord-jdbcpostgresql-adapter'
  end
end
