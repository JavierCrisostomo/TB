source :rubygems unless ENV['QUICK']

%w[sinatra rack].each { |d| gem(d, :git => "git://github.com/rkh/#{d}.git") }
%w[tilt slim sass rdiscount compass coffee-script thin builder].each { |d| gem(d) }

