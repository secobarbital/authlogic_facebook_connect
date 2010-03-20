require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "secobarbital-authlogic_facebook_connect"
    gem.summary = %Q{Extension of the Authlogic library to add Facebook Connect support built upon the excellent facebooker gem}
    gem.email = ["jocke.ekberg@gmail.com", "sumboh@thingbuzz.com"]
    gem.homepage = "http://github.com/kalasjocke/authlogic_facebook_connect"
    gem.authors = ["Joakim Ekberg", "Seggy Umboh"]

    gem.add_dependency "authlogic"
    gem.add_dependency "facebooker"
    
    gem.files.exclude ".gitignore"
    gem.files.exclude "*.gemspec"
  end
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end