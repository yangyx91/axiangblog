---
layout: post
title:  "Build and start first blog!"
date:   2021-04-22 14:22:27 +0800
categories: jekyll
author: Jeffrey
---
Switch to a folder where you wish to store your sites configuration files,Execute the following command to build and serve your new site
bundle exec `jekyll serve`

### Command 

```command
D:\myblog\myblog>jekyll serve
Configuration file: D:/myblog/myblog/_config.yml
            Source: D:/myblog/myblog
       Destination: D:/myblog/myblog/_site
 Incremental build: disabled. Enable with --incremental
      Generating...
       Jekyll Feed: Generating feed for posts
                    done in 1.556 seconds.
 Auto-regeneration: enabled for 'D:/myblog/myblog'
    Server address: http://127.0.0.1:4000/
  Server running... press ctrl-c to stop.
  ```
  
Browse to http://localhost:4000/ (note the http not https).
The console output from 'bundle exec jekyll serve
You now have a tiny webserver running inside your command window hosting a new Jekyll site; visit http://localhost:4000 to view it.

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
