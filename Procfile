web: bundle exec rails server ${RAILS_SERVER:webrick} -b 0.0.0.0 -p ${PORT:-3000} -e ${RAILS_ENV:-development}
worker: bundle exec rails runner bin/threaded.rb
