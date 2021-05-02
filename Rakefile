require 'puppetfile-updater/task'

PuppetfileUpdater::RakeTask.new :sync_refs do |config|
  # Add gh_token config to avoid hitting the GitHub connection rate
  #config.gh_token    = '...'
  config.major       = true
  config.debug       = true
end
