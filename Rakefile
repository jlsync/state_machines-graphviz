require 'rubygems'
require 'bundler/setup'

require 'rspec/core/rake_task'
RSpec::Core::RakeTask.new do |t|
  t.pattern = 'spec/**/*_spec.rb'
end

desc 'Default: run all tests.'
task :default => :spec

load File.dirname(__FILE__) + '/lib/state_machines/tasks/state_machines.rake'