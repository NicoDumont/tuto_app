# Tutoriel Ruby on Rails : Application Exemple

C'est l'Application Exemple pour le
[*Tutoriel Ruby on Rails : Apprendre Rails par l'exemple*](http://railstutorial.org/)
par [Michael Hartl](http://michaelhartl.com/).

vagrant@simruby-devbox:/vagrant/tuto_app$ ruby -v
ruby 2.0.0p247 (2013-06-27 revision 41674) [x86_64-linux]
vagrant@simruby-devbox:/vagrant/tuto_app$ rails -v
Rails 3.1.12


source 'http://rubygems.org'
gem "rails", "~> 3.1.0"
gem 'sqlite3', '1.3.3'
group :development do
gem 'rspec-rails', '2.6.1'
end
group :test do
gem 'rspec-rails', '2.6.1'
gem 'webrat', '0.7.1'
end