web: bundle exec rackup --host 0.0.0.0 --port ${PORT:-3000} --env ${RAILS_ENV:-development} --server ${SERVER:-webrick}
worker: bundle exec rails runner bin/threaded.rb
