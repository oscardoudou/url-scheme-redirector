URL Scheme Redirector
===============
If you run this app locally, by prefixing your custom scheme with `localhost:3000/`, your could turn url scheme into recognizable URL.

### Usage  
For example. On Mac, email custom scheme is `message://<message-id>`. You could use it in Chrome, Safari. But if you try to use it as URL in Notion, as of Dec 5th, 2021, Notion would only treat it as a page.     

To work around, provide an URL like `localhost:3000/message://<message-id>` instead. Notion will open it in browser when you click it, from there it acts just the same as you put custom scheme in browser.  

