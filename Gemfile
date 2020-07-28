source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'#(対象のRubyバージョン)

gem 'rails', '~> 6.0.3', '>= 6.0.3.2' #(対象のRailsバージョン)
gem 'sqlite3', '~> 1.4'#(sqlite3をインストール)
gem 'puma', '~> 4.1'#(Railsを動かすためのサーバ)
gem 'sass-rails', '>= 6'  #(Sassが使える)
gem 'webpacker', '~> 4.0'#(webpackerが使える)
gem 'turbolinks', '~> 5'#(Ajaxに置き換え.高速化するgem)
gem 'jbuilder', '~> 2.7' #（JSON API関係？）
gem 'bootsnap', '>= 1.4.2', require: false #(Bootstrapが使える)

#追加したgem
gem 'pry-rails' #(デバックツール)

group :development, :test do  #(開発環境とテスト環境のみ対象)
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  #追加したgem
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  #追加したgem
  
end

group :test do  #(テスト環境のみインストール)
  gem 'capybara', '>= 2.15'#(テスト時に役立つ)
  gem 'selenium-webdriver'#(テスト時に役立つ)
  gem 'webdrivers'
  #追加したgem

end


gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
