# -*- ruby -*-

# To regenerate gemspec for github
# rake debug_gem > stompserver.gemspec

require 'rubygems'
require 'hoe'
$LOAD_PATH << "./lib"
require 'stomp_server'

Hoe.spec('stompserver') do |p|
  p.rubyforge_name = 'stompserver'
  p.summary = 'A very light messaging server'
  p.description = "It's a messaging server."
  p.url = 'http://github.com/HitTheSticks/stompserver'
  p.email = [ "aubrey@greyhelix.com", "lionel-dev@bouton.name" ]
  p.author = [ "Aubrey Jones", "Lionel Bouton" ]
  p.extra_deps = [
    # This depencency is real, but if you are on a Win32 box
    # and don't have VC6, it can be a real problem
    ["daemons", ">= 1.0.2"],
    ["eventmachine", ">= 0.7.2"],
    ["hoe", ">= 1.1.1"],
  ]
  p.remote_rdoc_dir = ''
end

# vim: syntax=Ruby
