GLUE_ROOT = File.dirname(__FILE__)

require "glue/rake"

task :deploy => ['glue:generate'] do
  puts `rsync -av --delete public/ oaqn@blog.oaqn.com:soplayweall.com`
end
