
begin
    require 'jeweler'
    Jeweler::Tasks.new do |gemspec|
        gemspec.name = "jkarlsson-mini_fb"
        gemspec.summary = "Tiny facebook library"
        gemspec.description = "Tiny facebook library. This fork adds video upload support"
        gemspec.email = "travis@appoxy.com"
        gemspec.homepage = "http://github.com/jkarlsson/mini_fb"
        gemspec.authors = ["Travis Reeder"]
        gemspec.files = FileList['lib/**/*.rb']
        gemspec.add_dependency 'rest-client'
        gemspec.add_dependency 'hashie'
        gemspec.add_dependency 'mime-types'
    end
    Jeweler::GemcutterTasks.new
rescue LoadError
    puts "Jeweler not available. Install it with: sudo gem install technicalpickles-jeweler -s http://gems.github.com"
end
