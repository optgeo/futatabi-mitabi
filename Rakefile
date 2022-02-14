require './constants'

desc 'serve'
task :serve do
  sh <<-EOS
ruby serve.rb -p #{PORT}
  EOS
end

desc 'build'
task :build do
  sh <<-EOS
charites --provider mapbox build style.yml docs/style.json
  EOS
end

