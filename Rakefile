task :default do
  timestamp = Time.now.strftime("%Y%m%d")
  `zip -r ../duckduckgo-#{timestamp}.zip dashlet/ LICENSE.txt manifest.php README.txt en_us.lang.php -x "*.DS_Store"`
end
