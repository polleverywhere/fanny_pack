spec_location = "spec/javascripts/%s_spec"

guard 'jasmine-headless-webkit', :all_on_start => false do
  watch(%r{^source/javascripts/(.*)\.(js|coffee)$}) { |m| newest_js_file(spec_location % m[1]) }
  watch(%r{^spec/javascripts/(.*)_spec\..*}) { |m| newest_js_file(spec_location % m[1]) }
end
