

# TO DO S:

- Fix pagesbar on mobile,
- Make the cover fotos change from time to time -> debug the function to show cover photo!
- Refactor messy code
- Change layout for travel page to show bigger fotos
- Decide what is useless and delete it
- Try to change header and head to use Beautiful Jekil recent implementation without compilation problems
- Learn in local development: tired of waiting for github deploy!
- Add about me page
- write blog description

### YAML front matter parameters


Parameter   | Description
----------- | -----------
title       | Page or blog post title
subtitle    | Short description of page or blog post that goes under the title
bigimg      | Include a large full-width image at the top of the page.  You can either give the path to a single image, or provide a list of images to cycle through (see [my personal website](http://deanattali.com/) as an example).
comments    | If you want do add Disqus comments to a specific page, use `comments: true`. Comments are automatically enabled on blog posts; to turn comments off for a specific post, use `comments: false`. Comments only work if you set your Disqus id in the `_config.yml` file.
show-avatar | If you have an avatar configured in the `_config.yml` but you want to turn it off on a specific page, use `show-avatar: false`. If you want to turn it off by default, locate the line `show-avatar: true` in the file `_config.yml` and change the `true` to `false`; then you can selectively turn it on in specific pages using `show-avatar: true`.
image       | If you want to add a personalized image to your blog post that will show up next to the post's excerpt and on the post itself, use `image: /path/to/img`.
share-img   | If you want to specify an image to use when sharing the page on Facebook or Twitter, then provide the image's full URL here.
social-share | If you don't want to show buttons to share a blog post on social media, use `social-share: false` (this feature is turned on by default).
use-site-title | If you want to use the site title rather than page title as HTML document title (ie. browser tab title), use `use-site-title: true`. When set, the document title will take the format `Site Title - Site Description` (eg. `My website - A virtual proof that name is awesome!`). By default, it will use `Page Title` if it exists, or `Site Title` otherwise.
layout      | What type of page this is (default is `blog` for blog posts and `page` for other pages. You can use `minimal` if you don't want a header and footer)  
js          | List of local JavaScript files to include in the page (eg. `/js/mypage.js`)
ext-js      | List of external JavaScript files to include in the page (eg. `//cdnjs.cloudflare.com/ajax/libs/underscore.js/1.8.2/underscore-min.js`). External JavaScript files that support [Subresource Integrity (SRI)](https://developer.mozilla.org/en-US/docs/Web/Security/Subresource_Integrity) can be specified using the `href` and `sri` parameters eg.<br/>`href: "//code.jquery.com/jquery-3.1.1.min.js"`<br/>`sri: "sha256-hVVnYaiADRTO2PzUGmuLJr8BLUSjGIZsDYGmIJLv2b8="`
css         | List of local CSS files to include in the page
ext-css      | List of external CSS files to include in the page. External CSS files using SRI (see `ext-js` parameter) are also supported. 
googlefonts | List of Google fonts to include in the page (eg. `["Monoton", "Lobster"]`)


Most of this code was originally from beautifulljekyl project. I did a few editions on my version, and the version i initially forked carried some modification too.
