# frozen_string_literal: true

# Copyright The OpenTelemetry Authors
#
# SPDX-License-Identifier: Apache-2.0

source 'https://rubygems.org'

# DO NOT ADD DEPENDENCIES HERE!
# Please declare a minimum development dependency in the gemspec,
# then target specific versions in the Appraisals file.

#gem 'opentelemetry-instrumentation-base', path: '/Users/josecarlostubadeza/RubyProjects/opentelemetry-instrumentation-base-ruby2.6-experimental'
#gem 'opentelemetry-instrumentation-base', '~> 0.21.1'
gem 'opentelemetry-instrumentation-rack', git: 'https://github.com/LoyalSphere/opentelemetry-instrumentation-rack-ruby2.6-experimental', branch: 'master'

gemspec

group :test do
  #gem 'opentelemetry-instrumentation-base', path: '../base'
  #gem 'opentelemetry-instrumentation-rack', path: '../rack'

  #gem 'opentelemetry-instrumentation-base', path: '../opentelemetry-ruby-contrib-ruby2.7-experimental/instrumentation/base'
  #gem 'opentelemetry-instrumentation-base', '~> 0.22.1' #Ruby 3.0
  gem 'opentelemetry-instrumentation-base', '~> 0.21.1'  #Ruby 2.6

  #gem 'opentelemetry-instrumentation-rack', '~> 0.21'
end
