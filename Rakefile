require 'bundler/setup'
Bundler::GemHelper.install_tasks

require 'rspec/core/rake_task'

desc 'Run all examples'
RSpec::Core::RakeTask.new(:spec) do |t|
  # t.rspec_path = 'bin/rspec'
  t.rspec_opts = %w(--color)
end

task default: :spec
