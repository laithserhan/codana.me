task :deploy

task :deploy do |t|
  sh "git push origin master"
  sh "./deploy"
end

task :default => [:deploy]
