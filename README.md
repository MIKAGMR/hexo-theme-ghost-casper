# hexo-theme-ghost-casper
[Ghost Casper](https://github.com/TryGhost/Casper) v1.1.5 hexo port.  
Basic structure from [hexo-theme-casper](https://github.com/kywk/hexo-theme-casper)

[Demo](http://mikagmr.github.io/hexo-theme-ghost-casper-demo/)


##Installation

###Install

``` bash
$ git clone https://github.com/MIKAGMR/hexo-theme-ghost-casper.git themes/ghost-casper
```

###Enable

Change `theme` setting in `_config.yml` to `ghost-casper`.

##Configuration
###Global config
Add in theme `_config.yml`:

``` yml
cover: //blog.ghost.org/content/images/2013/Nov/cover.png

bio: 'A designer, developer and entrepreneur. Spends his time travelling the world with a bag of kites. Likes journalism and publishing platforms.'
location: Earth
website: https://www.website.com
social:
  twitter: https://twitter.com/**profile**
  google+: https://plus.google.com/**profile**
```

####Fancybox
Load plugin per post.
Remove entry from theme `_config.yml`.  
Add in the Frontend-matter:
``` yml
fancybox: true
```

####fitvids
Load plugin per post.  
Add in the Frontend-matter:
``` yml
fitvids: true
```

###Per post config

####Post cover image
Add in the Frontend-matter:
``` yml
cover: path/to/image
```

####Fancybox
Load plugin per post.
Remove entry from theme `_config.yml`.  
Add in the Frontend-matter:
``` yml
fancybox: true
```

####fitvids
Load plugin per post.  
Remove entry from theme `_config.yml`.  
Add in the Frontend-matter:
``` yml
fitvids: true
```

For more configuration settings read the [hexo documentation](http://hexo.io/docs/configuration.html).

## Copyright & License

### Casper Theme
Copyright (c) 2013-2015 Ghost Foundation - Released under the MIT License.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

### Normalize

Copyright (c) Nicolas Gallagher and Jonathan Neal

Permission is hereby granted, free of charge, to any person obtaining a copy of
this software and associated documentation files (the "Software"), to deal in
the Software without restriction, including without limitation the rights to
use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies
of the Software, and to permit persons to whom the Software is furnished to do
so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
