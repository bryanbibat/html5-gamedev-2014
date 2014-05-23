guard 'puma', :port => 3000 do
  watch('Gemfile.lock')
  watch('app.rb')
end

guard 'livereload' do
  watch(%r{public/.+\.(js)$})
end
