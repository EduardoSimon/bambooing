require "bundler/gem_tasks"
require "rspec/core/rake_task"
import 'lib/tasks/create_current_weekdays.rake'
import 'lib/tasks/create_current_month_weekdays.rake'
import 'lib/tasks/create_custom_dates_weekdays.rake'

RSpec::Core::RakeTask.new(:spec)

task :default => :spec
