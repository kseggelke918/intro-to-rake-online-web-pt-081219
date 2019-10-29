namespace :greeting do 
desc 'outputs hello to the terminal'
task :hello do
  puts "hello from Rake!"
end

desc 'outputs hola to the terminal'
task :hola do 
  puts "hola de Rake!"
end 
end 

namespace :db do 
  desc 'migrates changes to your database'
  task :migrate => :environment do 
    Student.create_table
  end 
end 

  desc 'connection to enviroment.rb'
  task :environment do 
    require_relative './config/environment'
  end 