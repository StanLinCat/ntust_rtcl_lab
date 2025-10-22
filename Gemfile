# frozen_string_literal: true

source "https://rubygems.org"

# --- 核心依賴 ---
gem "jekyll"
gem "webrick", "~> 1.7" 

# --- Sass 編譯器強制指定 ---
# 確保使用 sassc 編譯器
gem "sassc" 

# 使用舊版 jekyll-sass-converter，確保它使用 sassc 而非 sass-embedded
# jekyll-sass-converter 3.x 開始使用 sass-embedded，我們降級到 2.x
gem "jekyll-sass-converter", "~> 2.1" 


# --- 外掛 ---
group :jekyll_plugins do
  gem 'jekyll-scholar'
end