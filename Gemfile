source 'https://rubygems.org'

# Specify your gem's dependencies in pact.gemspec
gemspec

if ENV['X_PACT_DEVELOPMENT']
  gem 'pact-support', path: '../pact-support'
else
  gem "pact-support", git: 'https://github.com/safdotdev/pact-support.git', branch: 'feat/pact_v3_matcher_format'
end