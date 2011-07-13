GLUE_ROOT = File.dirname(__FILE__)

require "glue/rake"

task :deploy => ['glue:generate'] do
  puts `rsync -av --delete public/ soplayweall@soplayweall.com:soplayweall.com`
  puts 'git push origin master'
end
