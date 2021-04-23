---
layout: post
title:  "install jekyll bundler!"
date:   2021-04-22 14:22:27 +0800
categories: jekyll
---
We only cover RubyInstaller-2.4 and newer here. Older versions need to install the Devkit manually.

Download and install a Ruby+Devkit version from RubyInstaller Downloads:https://rubyinstaller.org/downloads/. Use default options for installation.

Run the `ridk install` step on the last stage of the installation wizard. This is needed for installing gems with native extensions. 

Open a new command prompt window from the start menu, so that changes to the PATH environment variable becomes effective. Install Jekyll and Bundler using : `gem install jekyll bundler`

#### Command


```command
C:\Ruby27-x64>gem install jekyll bundler
Fetching public_suffix-4.0.6.gem
Fetching addressable-2.7.0.gem
Fetching colorator-1.1.0.gem
Fetching eventmachine-1.2.7-x64-mingw32.gem
Fetching http_parser.rb-0.6.0.gem
Fetching em-websocket-0.5.2.gem
Fetching concurrent-ruby-1.1.8.gem
Fetching i18n-1.8.10.gem
Fetching ffi-1.15.0-x64-mingw32.gem
Fetching sassc-2.4.0-x64-mingw32.gem
Fetching jekyll-sass-converter-2.1.0.gem
Fetching rb-fsevent-0.10.4.gem
Fetching rb-inotify-0.10.1.gem
Fetching listen-3.5.1.gem
Fetching jekyll-watch-2.2.1.gem
Fetching kramdown-2.3.1.gem
Fetching kramdown-parser-gfm-1.1.0.gem
Fetching liquid-4.0.3.gem
Fetching mercenary-0.4.0.gem
Fetching forwardable-extended-2.6.0.gem
Fetching pathutil-0.16.2.gem
Fetching rouge-3.26.0.gem
Fetching safe_yaml-1.0.5.gem
Fetching unicode-display_width-1.7.0.gem
Fetching jekyll-4.2.0.gem
Fetching terminal-table-2.0.0.gem
Successfully installed public_suffix-4.0.6
Successfully installed addressable-2.7.0
Successfully installed colorator-1.1.0
Successfully installed eventmachine-1.2.7-x64-mingw32
Temporarily enhancing PATH for MSYS/MINGW...
Building native extensions. This could take a while...
Successfully installed http_parser.rb-0.6.0
Successfully installed em-websocket-0.5.2
Successfully installed concurrent-ruby-1.1.8
Successfully installed i18n-1.8.10
Successfully installed ffi-1.15.0-x64-mingw32
Successfully installed sassc-2.4.0-x64-mingw32
Successfully installed jekyll-sass-converter-2.1.0
Successfully installed rb-fsevent-0.10.4
Successfully installed rb-inotify-0.10.1
Successfully installed listen-3.5.1
Successfully installed jekyll-watch-2.2.1
Successfully installed kramdown-2.3.1
Successfully installed kramdown-parser-gfm-1.1.0
Successfully installed liquid-4.0.3
Successfully installed mercenary-0.4.0
Successfully installed forwardable-extended-2.6.0
Successfully installed pathutil-0.16.2
Successfully installed rouge-3.26.0
Successfully installed safe_yaml-1.0.5
Successfully installed unicode-display_width-1.7.0
Successfully installed terminal-table-2.0.0
Successfully installed jekyll-4.2.0
Parsing documentation for public_suffix-4.0.6
Installing ri documentation for public_suffix-4.0.6
Parsing documentation for addressable-2.7.0
Installing ri documentation for addressable-2.7.0
Parsing documentation for colorator-1.1.0
Installing ri documentation for colorator-1.1.0
Parsing documentation for eventmachine-1.2.7-x64-mingw32
Installing ri documentation for eventmachine-1.2.7-x64-mingw32
Parsing documentation for http_parser.rb-0.6.0
unknown encoding name "chunked\r\n\r\n25" for ext/ruby_http_parser/vendor/http-p
arser-java/tools/parse_tests.rb, skipping
Installing ri documentation for http_parser.rb-0.6.0
Parsing documentation for em-websocket-0.5.2
Installing ri documentation for em-websocket-0.5.2
Parsing documentation for concurrent-ruby-1.1.8
Installing ri documentation for concurrent-ruby-1.1.8
Parsing documentation for i18n-1.8.10
Installing ri documentation for i18n-1.8.10
Parsing documentation for ffi-1.15.0-x64-mingw32
Installing ri documentation for ffi-1.15.0-x64-mingw32
Parsing documentation for sassc-2.4.0-x64-mingw32
Installing ri documentation for sassc-2.4.0-x64-mingw32
Parsing documentation for jekyll-sass-converter-2.1.0
Installing ri documentation for jekyll-sass-converter-2.1.0
Parsing documentation for rb-fsevent-0.10.4
Installing ri documentation for rb-fsevent-0.10.4
Parsing documentation for rb-inotify-0.10.1
Installing ri documentation for rb-inotify-0.10.1
Parsing documentation for listen-3.5.1
Installing ri documentation for listen-3.5.1
Parsing documentation for jekyll-watch-2.2.1
Installing ri documentation for jekyll-watch-2.2.1
Parsing documentation for kramdown-2.3.1
Installing ri documentation for kramdown-2.3.1
Parsing documentation for kramdown-parser-gfm-1.1.0
Installing ri documentation for kramdown-parser-gfm-1.1.0
Parsing documentation for liquid-4.0.3
Installing ri documentation for liquid-4.0.3
Parsing documentation for mercenary-0.4.0
Installing ri documentation for mercenary-0.4.0
Parsing documentation for forwardable-extended-2.6.0
Installing ri documentation for forwardable-extended-2.6.0
Parsing documentation for pathutil-0.16.2
Installing ri documentation for pathutil-0.16.2
Parsing documentation for rouge-3.26.0
Installing ri documentation for rouge-3.26.0
Parsing documentation for safe_yaml-1.0.5
Installing ri documentation for safe_yaml-1.0.5
Parsing documentation for unicode-display_width-1.7.0
Installing ri documentation for unicode-display_width-1.7.0
Parsing documentation for terminal-table-2.0.0
Installing ri documentation for terminal-table-2.0.0
Parsing documentation for jekyll-4.2.0
Installing ri documentation for jekyll-4.2.0
Done installing documentation for public_suffix, addressable, colorator, eventma
chine, http_parser.rb, em-websocket, concurrent-ruby, i18n, ffi, sassc, jekyll-s
ass-converter, rb-fsevent, rb-inotify, listen, jekyll-watch, kramdown, kramdown-
parser-gfm, liquid, mercenary, forwardable-extended, pathutil, rouge, safe_yaml,
 unicode-display_width, terminal-table, jekyll after 61 seconds
Successfully installed bundler-2.2.16
Parsing documentation for bundler-2.2.16
Done installing documentation for bundler after 5 seconds
27 gems installed
```

Check if Jekyll has been installed properly: jekyll -v

``` command line
C:\Ruby27-x64>jekyll -v
jekyll 4.2.0
```


Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
