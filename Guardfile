ignore %r{.nfs\h+}, %r{.swp$}, %r{~$}

guard 'jade', :output => 'build', :all_on_start => true do
  watch(%r{^src/(.+\.jade$)})
end

