# Web Knowledge Invokers - 2
The art of SEO has become a science in recent years, but some foundation requirements are expected from developers. This "WKP" is going to focus on basic SEO requirements within any website.

Three main tags are required to be set in the head of the document:

### 1) Title
The title serves two purposes (mainly); 1) The title shown in the window of your browser and in Bookmarks, 2) Serves as the main title for your site as seen in search engine links.

### 2) Description
The description meta tag is the desription paragraph shown underneath the link in the Google search results (SERPs) - this is also used (albeit a minor usage) in the ranking and idnexation of a webpage:

  <meta name="description" content="Mark's amazing whisky blog - providing independent reviews and analysis of the industry's favourite whisky">

### 3) Canonical
Canonical links tell Google and Bing which URL is the correct url to index when the same content can be seen on multiple pages. For example lets assume that the below two dynamic links point to the same content:

  http://www.example.com/blog/my-great-blog
  ...and...
  http://www.example.com/blog/?p=2

Google would index both pages, and they would be in competition for search traffic - this is where canonical links come in - setting the canonical on the site to the first link (example below) will mean that Google and Bing will only link to (index) that URL:

  <meta name="canonical" content="http://www.example.com/blog/my-great-blog">

### Word on Keywords Meta Tag
You may have heard of this tag from many online sources, or seen it within the source code of websites - this tag is no longer used or supported by the major search engines.

Modern search engines use a profiling aproach to understanding the content of a website or a page.

# Until next time!
