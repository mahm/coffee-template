guard 'haml', output: 'www', input: 'src/haml', bare: true do
  watch %r{^src/haml/(.*/)?([^/]+)(\.html\.haml)$}
end

compass = {
  images_dir: 'img',
  images_path: File.join(Dir.pwd, 'img'),
  http_images_path: '/',
  http_images_dir: '/img'
}
guard :sass, output: 'www/css', input: 'src/sass', bare: true, compass: compass do
  watch %r{^src/sass/(.*/)?([^/]+)\.sass$}
end

guard :coffeescript, output: 'www/js', input: 'src/coffee', bare: true do
  watch %r{^src/coffee/(.*/)?([^/]+)\.coffee$}
end
