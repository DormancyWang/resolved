require "capistrano/setup"
require "capistrano/deploy"
require "capistrano/rbenv"
require "capistrano/scm/git"
install_plugin Capistrano::SCM::Git
require "capistrano/bundler"
require "capistrano/puma"

Dir.glob("lib/capistrano/tasks/*.rake").each { |r| import r }
