require "bundler/setup"

load "rails/tasks/statistics.rake"

require "bundler/gem_tasks"


require 'rspec/core'
require 'rspec/core/rake_task'

desc "Run all specs in spec directory (excluding plugin specs)"
RSpec::Core::RakeTask.new(:spec)

task :default => :spec
