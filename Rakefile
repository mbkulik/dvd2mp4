task :default => [:install]

prog='dvd2mp4'

task :install do
     FileUtils.cp prog, "#{Dir.home}/bin"
end

task :uninstall do
     FileUtils.rm "#{Dir.home}/bin/#{prog}"
end
