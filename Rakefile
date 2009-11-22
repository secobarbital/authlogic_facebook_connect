require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "authlogic_facebook_connect"
    gem.summary = %Q{Extension of the Authlogic library to add Facebook Connect support built upon the excellent facebooker gem}
    # gem.description = %Q{}
    # gem.email = ""
    gem.homepage = "http://github.com/kalasjocke/authlogic_facebook_connect"
    gem.authors = ["kalasjocke"]

    gem.add_dependency("facebooker")
    gem.add_dependency("authlogic")
    # gem is a Gem::Specification... see http://www.rubygems.org/read/chapter/20 for additional settings
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end