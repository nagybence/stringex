# coding: utf-8

require 'rake'
require 'rake/testtask'
require 'rake/rdoctask'

begin
  require 'jeweler'
  Jeweler::Tasks.new do |gem|
    gem.name        = "stringex"
    gem.authors     = ["Russell Norris"]
    gem.email       = "rsl@luckysneaks.com"
    gem.homepage    = "http://github.com/rsl/stringex"
    gem.summary     = "Some [hopefully] useful extensions to Ruby's String class"
    gem.description = "Some [hopefully] useful extensions to Ruby's String class. Stringex is made up of three libraries: ActsAsUrl [permalink solution with better character translation], Unidecoder [Unicode to ASCII transliteration], and StringExtensions [miscellaneous helper methods for the String class]."
    gem.has_rdoc    = true
    gem.files       = %w{
      init.rb
      MIT-LICENSE
      Rakefile
      README.rdoc
      stringex.gemspec
      lib/stringex.rb
      lib/stringex/acts_as_url.rb
      lib/stringex/string_extensions.rb
      lib/stringex/unidecoder.rb
      lib/stringex/unidecoder_data/x00.yml
      lib/stringex/unidecoder_data/x01.yml
      lib/stringex/unidecoder_data/x02.yml
      lib/stringex/unidecoder_data/x03.yml
      lib/stringex/unidecoder_data/x04.yml
      lib/stringex/unidecoder_data/x05.yml
      lib/stringex/unidecoder_data/x06.yml
      lib/stringex/unidecoder_data/x07.yml
      lib/stringex/unidecoder_data/x09.yml
      lib/stringex/unidecoder_data/x0a.yml
      lib/stringex/unidecoder_data/x0b.yml
      lib/stringex/unidecoder_data/x0c.yml
      lib/stringex/unidecoder_data/x0d.yml
      lib/stringex/unidecoder_data/x0e.yml
      lib/stringex/unidecoder_data/x0f.yml
      lib/stringex/unidecoder_data/x10.yml
      lib/stringex/unidecoder_data/x11.yml
      lib/stringex/unidecoder_data/x12.yml
      lib/stringex/unidecoder_data/x13.yml
      lib/stringex/unidecoder_data/x14.yml
      lib/stringex/unidecoder_data/x15.yml
      lib/stringex/unidecoder_data/x16.yml
      lib/stringex/unidecoder_data/x17.yml
      lib/stringex/unidecoder_data/x18.yml
      lib/stringex/unidecoder_data/x1e.yml
      lib/stringex/unidecoder_data/x1f.yml
      lib/stringex/unidecoder_data/x20.yml
      lib/stringex/unidecoder_data/x21.yml
      lib/stringex/unidecoder_data/x22.yml
      lib/stringex/unidecoder_data/x23.yml
      lib/stringex/unidecoder_data/x24.yml
      lib/stringex/unidecoder_data/x25.yml
      lib/stringex/unidecoder_data/x26.yml
      lib/stringex/unidecoder_data/x27.yml
      lib/stringex/unidecoder_data/x28.yml
      lib/stringex/unidecoder_data/x2e.yml
      lib/stringex/unidecoder_data/x2f.yml
      lib/stringex/unidecoder_data/x30.yml
      lib/stringex/unidecoder_data/x31.yml
      lib/stringex/unidecoder_data/x32.yml
      lib/stringex/unidecoder_data/x33.yml
      lib/stringex/unidecoder_data/x4d.yml
      lib/stringex/unidecoder_data/x4e.yml
      lib/stringex/unidecoder_data/x4f.yml
      lib/stringex/unidecoder_data/x50.yml
      lib/stringex/unidecoder_data/x51.yml
      lib/stringex/unidecoder_data/x52.yml
      lib/stringex/unidecoder_data/x53.yml
      lib/stringex/unidecoder_data/x54.yml
      lib/stringex/unidecoder_data/x55.yml
      lib/stringex/unidecoder_data/x56.yml
      lib/stringex/unidecoder_data/x57.yml
      lib/stringex/unidecoder_data/x58.yml
      lib/stringex/unidecoder_data/x59.yml
      lib/stringex/unidecoder_data/x5a.yml
      lib/stringex/unidecoder_data/x5b.yml
      lib/stringex/unidecoder_data/x5c.yml
      lib/stringex/unidecoder_data/x5d.yml
      lib/stringex/unidecoder_data/x5e.yml
      lib/stringex/unidecoder_data/x5f.yml
      lib/stringex/unidecoder_data/x60.yml
      lib/stringex/unidecoder_data/x61.yml
      lib/stringex/unidecoder_data/x62.yml
      lib/stringex/unidecoder_data/x63.yml
      lib/stringex/unidecoder_data/x64.yml
      lib/stringex/unidecoder_data/x65.yml
      lib/stringex/unidecoder_data/x66.yml
      lib/stringex/unidecoder_data/x67.yml
      lib/stringex/unidecoder_data/x68.yml
      lib/stringex/unidecoder_data/x69.yml
      lib/stringex/unidecoder_data/x6a.yml
      lib/stringex/unidecoder_data/x6b.yml
      lib/stringex/unidecoder_data/x6c.yml
      lib/stringex/unidecoder_data/x6d.yml
      lib/stringex/unidecoder_data/x6e.yml
      lib/stringex/unidecoder_data/x6f.yml
      lib/stringex/unidecoder_data/x70.yml
      lib/stringex/unidecoder_data/x71.yml
      lib/stringex/unidecoder_data/x72.yml
      lib/stringex/unidecoder_data/x73.yml
      lib/stringex/unidecoder_data/x74.yml
      lib/stringex/unidecoder_data/x75.yml
      lib/stringex/unidecoder_data/x76.yml
      lib/stringex/unidecoder_data/x77.yml
      lib/stringex/unidecoder_data/x78.yml
      lib/stringex/unidecoder_data/x79.yml
      lib/stringex/unidecoder_data/x7a.yml
      lib/stringex/unidecoder_data/x7b.yml
      lib/stringex/unidecoder_data/x7c.yml
      lib/stringex/unidecoder_data/x7d.yml
      lib/stringex/unidecoder_data/x7e.yml
      lib/stringex/unidecoder_data/x7f.yml
      lib/stringex/unidecoder_data/x80.yml
      lib/stringex/unidecoder_data/x81.yml
      lib/stringex/unidecoder_data/x82.yml
      lib/stringex/unidecoder_data/x83.yml
      lib/stringex/unidecoder_data/x84.yml
      lib/stringex/unidecoder_data/x85.yml
      lib/stringex/unidecoder_data/x86.yml
      lib/stringex/unidecoder_data/x87.yml
      lib/stringex/unidecoder_data/x88.yml
      lib/stringex/unidecoder_data/x89.yml
      lib/stringex/unidecoder_data/x8a.yml
      lib/stringex/unidecoder_data/x8b.yml
      lib/stringex/unidecoder_data/x8c.yml
      lib/stringex/unidecoder_data/x8d.yml
      lib/stringex/unidecoder_data/x8e.yml
      lib/stringex/unidecoder_data/x8f.yml
      lib/stringex/unidecoder_data/x90.yml
      lib/stringex/unidecoder_data/x91.yml
      lib/stringex/unidecoder_data/x92.yml
      lib/stringex/unidecoder_data/x93.yml
      lib/stringex/unidecoder_data/x94.yml
      lib/stringex/unidecoder_data/x95.yml
      lib/stringex/unidecoder_data/x96.yml
      lib/stringex/unidecoder_data/x97.yml
      lib/stringex/unidecoder_data/x98.yml
      lib/stringex/unidecoder_data/x99.yml
      lib/stringex/unidecoder_data/x9a.yml
      lib/stringex/unidecoder_data/x9b.yml
      lib/stringex/unidecoder_data/x9c.yml
      lib/stringex/unidecoder_data/x9d.yml
      lib/stringex/unidecoder_data/x9e.yml
      lib/stringex/unidecoder_data/x9f.yml
      lib/stringex/unidecoder_data/xa0.yml
      lib/stringex/unidecoder_data/xa1.yml
      lib/stringex/unidecoder_data/xa2.yml
      lib/stringex/unidecoder_data/xa3.yml
      lib/stringex/unidecoder_data/xa4.yml
      lib/stringex/unidecoder_data/xac.yml
      lib/stringex/unidecoder_data/xad.yml
      lib/stringex/unidecoder_data/xae.yml
      lib/stringex/unidecoder_data/xaf.yml
      lib/stringex/unidecoder_data/xb0.yml
      lib/stringex/unidecoder_data/xb1.yml
      lib/stringex/unidecoder_data/xb2.yml
      lib/stringex/unidecoder_data/xb3.yml
      lib/stringex/unidecoder_data/xb4.yml
      lib/stringex/unidecoder_data/xb5.yml
      lib/stringex/unidecoder_data/xb6.yml
      lib/stringex/unidecoder_data/xb7.yml
      lib/stringex/unidecoder_data/xb8.yml
      lib/stringex/unidecoder_data/xb9.yml
      lib/stringex/unidecoder_data/xba.yml
      lib/stringex/unidecoder_data/xbb.yml
      lib/stringex/unidecoder_data/xbc.yml
      lib/stringex/unidecoder_data/xbd.yml
      lib/stringex/unidecoder_data/xbe.yml
      lib/stringex/unidecoder_data/xbf.yml
      lib/stringex/unidecoder_data/xc0.yml
      lib/stringex/unidecoder_data/xc1.yml
      lib/stringex/unidecoder_data/xc2.yml
      lib/stringex/unidecoder_data/xc3.yml
      lib/stringex/unidecoder_data/xc4.yml
      lib/stringex/unidecoder_data/xc5.yml
      lib/stringex/unidecoder_data/xc6.yml
      lib/stringex/unidecoder_data/xc7.yml
      lib/stringex/unidecoder_data/xc8.yml
      lib/stringex/unidecoder_data/xc9.yml
      lib/stringex/unidecoder_data/xca.yml
      lib/stringex/unidecoder_data/xcb.yml
      lib/stringex/unidecoder_data/xcc.yml
      lib/stringex/unidecoder_data/xcd.yml
      lib/stringex/unidecoder_data/xce.yml
      lib/stringex/unidecoder_data/xcf.yml
      lib/stringex/unidecoder_data/xd0.yml
      lib/stringex/unidecoder_data/xd1.yml
      lib/stringex/unidecoder_data/xd2.yml
      lib/stringex/unidecoder_data/xd3.yml
      lib/stringex/unidecoder_data/xd4.yml
      lib/stringex/unidecoder_data/xd5.yml
      lib/stringex/unidecoder_data/xd6.yml
      lib/stringex/unidecoder_data/xd7.yml
      lib/stringex/unidecoder_data/xf9.yml
      lib/stringex/unidecoder_data/xfa.yml
      lib/stringex/unidecoder_data/xfb.yml
      lib/stringex/unidecoder_data/xfc.yml
      lib/stringex/unidecoder_data/xfd.yml
      lib/stringex/unidecoder_data/xfe.yml
      lib/stringex/unidecoder_data/xff.yml
    }
    gem.test_files       = %w{
      test/acts_as_url_test.rb
      test/string_extensions_test.rb
      test/unidecoder_test.rb
    }
    gem.rdoc_options     = %w{--main README.rdoc --charset utf-8 --line-numbers}
    gem.extra_rdoc_files =  %w{MIT-LICENSE README.rdoc}
    gem.version = "1.3.2"
  end

  Jeweler::GemcutterTasks.new
rescue LoadError
  puts "Jeweler (or a dependency) not available. Install it with: sudo gem install jeweler"
end

desc 'Default: run unit tests.'
task :default => [:refresh_db, :test]

desc 'Remove old sqlite file.'
task :refresh_db do
  `rm -f #{File.dirname(__FILE__)}/test/acts_as_url.sqlite3`
end

desc 'Test the stringex plugin.'
Rake::TestTask.new(:test) do |t|
  t.libs << 'lib'
  t.pattern = 'test/**/*_test.rb'
  t.verbose = true
end

desc 'Generate documentation for the stringex plugin.'
Rake::RDocTask.new(:rdoc) do |rdoc|
  if File.exist?('VERSION.yml')
    config = YAML.load(File.read('VERSION.yml'))
    version = "#{config[:major]}.#{config[:minor]}.#{config[:patch]}"
  else
    version = ""
  end

  rdoc.rdoc_dir = 'rdoc'
  rdoc.title    = 'Stringex: A String Extension Pack [#{version}]'
  rdoc.options << '--line-numbers' << '--inline-source'
  rdoc.options << '--charset' << 'utf-8'
  rdoc.rdoc_files.include('README.rdoc')
  rdoc.rdoc_files.include('lib/**/*.rb')
end
