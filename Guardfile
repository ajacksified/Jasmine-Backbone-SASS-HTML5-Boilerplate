guard 'coffeescript', :output => 'client/js/app/compiled' do
  watch('^client/src/coffeescript/(.*)\.coffee')
end

guard 'coffeescript', :output => 'spec/javascripts' do
  watch('^spec/coffeescripts/(.*)\.coffee')
end

guard 'livereload', :apply_js_live => false do
  watch('^spec/javascripts/.+\.js$')
  watch('^client/js/app/compiled/.+\.js$')
end

guard 'sass', :input => 'client/src/sass', :output => 'client/css', :style => :compressed, :shallow => true, :all_on_start => true 
