require 'rubygems'
require 'rake'
require 'echoe'
require './lib/bitly.rb'

Echoe.new('bitly', Bitly::VERSION) do |p|
  p.description = "Use the bit.ly API to shorten or expand URLs"
  p.url = "http://github.com/philnash/bitly"
  p.author = "Phil Nash"
  p.email = "philnash@gmail.com"
  p.extra_deps      = [['crack', '>= 0.1.4'], ['httparty', '>= 0.5.2'], ['oauth2', '>= 0.1.1']]
  p.development_dependencies = []
end