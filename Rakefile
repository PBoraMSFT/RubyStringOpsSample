require 'rspec/core/rake_task'
task :default => :spec

desc "run tests for this app"
RSpec::Core::RakeTask.new(:spec) do |t|
  t.fail_on_error = false
  t.rspec_opts = "--no-drb -r rspec_junit_formatter --format RspecJunitFormatter -o TEST-rspec.xml"
end
