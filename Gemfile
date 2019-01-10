source "https://gems.ruby-china.com"
gem 'dotenv-rails', require: 'dotenv/rails-now'
gem "fastlane"
#如果使用 cocoapods管理项目依赖,增加下面的命令
gem "cocoapods"
plugins_path = File.join(File.dirname(__FILE__), 'fastlane', 'Pluginfile')
eval_gemfile(plugins_path) if File.exist?(plugins_path)
