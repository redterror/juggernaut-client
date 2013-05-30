require 'rubygems'
require 'rake'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name = "juggernaut-client"
    gem.summary = %Q{Simple realtime push}
    gem.description = %Q{Use Juggernaut to easily implement realtime chat, collaboration, gaming and much more!}
    gem.email = "dave@redterror.net"
    gem.homepage = "https://github.com/redterror/juggernaut-client"
    gem.authors = ["Alex MacCaw", "Dave Steinberg"]
    gem.add_dependency "redis", ">= 0"
  end
  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: gem install jeweler"
end
