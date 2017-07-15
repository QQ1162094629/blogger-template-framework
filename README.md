# Blogger Template Framework [![Build Status](https://camo.githubusercontent.com/f744ca9430339a123815b998fbf56e78a0582361/68747470733a2f2f7472617669732d63692e6f72672f626974636f696e2d636f72652f626974636f696e636f72652e6f72672e737667)](https://www.aguspurwantoro.com)
Great basic blogger templates with standard features and optimization.

Description
-----------
This template is made from scratch, with basic blogger features. This template is already optimize with seo, so you can focus on design and add more features. If seo on this template not good you can add seo techniques as you like.

Additional Code
-----------
Recent Post
~~~ .html
<script type="text/javascript">
function showrecentposts(json){for(var i=0;i<numposts;i++){var entry=json.feed.entry[i];var posttitle=entry.title.$t;var posturl;if(i==json.feed.entry.length)break;for(var k=0;k<entry.link.length;k++){if(entry.link[k].rel=='alternate'){posturl=entry.link[k].href;break}}posttitle=posttitle.link(posturl);if(standardstyling)document.write('<li>');document.write(posttitle)}if(standardstyling)document.write('</li>')}</script>
<script type="text/javascript">var numposts = 10;var showpostdate = true;var showpostsummary = true;var numchars = 100;var standardstyling = true;</script><script type="text/javascript" src="http://readcyber.blogspot.com/feeds/posts/default?orderby=published&amp;alt=json-in-script&amp;callback=showrecentposts"></script>
~~~

Important Link For Debugging
-----------
* [Structured Data Testing Tool](https://search.google.com/structured-data/testing-tool)
* [Mobile Friendly Testing Tool](https://search.google.com/search-console/mobile-friendly?utm_source=mft&utm_medium=link&utm_campaign=mft-upgrade-banner&hl=en-US)
* [HTML Validator](https://validator.w3.org/)
* [CSS Validator](https://jigsaw.w3.org/css-validator/)
* [Website Speedtest](https://gtmetrix.com/)
* [Page Speed Insights](https://developers.google.com/speed/pagespeed/insights/)

Thanks To
-----------
* [Google Developer](https://developers.google.com/web/))
* [Blogger API](https://www.blogger.com/api/v3)

License
-----------
The code is open source and available under the [MIT License](LICENSE.md).
