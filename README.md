# CMU_panoto_download

 Just a simple panoto downloader.

 Usage:
 1. Copy the text in Bookmarklet.js.
 
```javascript
javascript:(function()%7Bjavascript%3A(function()%7Bif(window.location.href.indexOf(%22panopto.com%22)%20%3C%201)%7Balert(%22No%20video%22)%3Bexit()%3B%7Dvar%20metas%20%3D%20document.getElementsByTagName('meta')%3Bfor%20(var%20i%3D0%3B%20i%3Cmetas.length%3B%20i%2B%2B)if%20(metas%5Bi%5D.getAttribute(%22name%22)%20%3D%3D%20%22twitter%3Aplayer%3Astream%22)%7Balert(%22The%20video%20adress%20is%3A%20%22%20%2B%20metas%5Bi%5D.getAttribute(%22content%22).split('%3F')%5B0%5D)%3B%7D%7D)()%7D)()
```

 2. Make a bookmark and paste the text in.
 3. Click the bookmark on panopto website and boom.

 ![howto](/howto.png)

 A tool for myself, no plan for maintenance.
 Don't know if this works for other Universities.
