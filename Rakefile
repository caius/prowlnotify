require "rake/gempackagetask"

spec = Gem::Specification.new do |s| 
  s.name = "prowlnotify"
  s.version = "0.2.1"
  s.author = "Caius Durling"
  s.email = "dev@caius.name"
  s.homepage = "http://github.com/caius/prowlnotify"
  s.platform = Gem::Platform::RUBY
  s.summary = "Easily send prowl notifications from the command line"
  s.bindir = "bin"
  s.files = FileList["lib/**/*.rb", "bin/*", "[A-Z]*", "spec/**/*"].to_a
  s.executables << "prowlnotify"
  s.has_rdoc = false
  s.add_dependency("prowl", "~> 0.1.3")
end
 
Rake::GemPackageTask.new(spec) do |pkg| 
  pkg.need_tar = true 
end 
