require 'bundler'
require 'rspec/core/rake_task'
require 'curdle'

Curdle::Tasks.install

require 'kuby'

task default: :spec

desc 'Run specs'
RSpec::Core::RakeTask.new do |t|
  t.pattern = './spec/**/*_spec.rb'
end
