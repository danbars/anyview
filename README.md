## Welcome to Anyview.link

### How to use anyview?

For now you can only view images. Just pass `img` query parameter and optional `bg`: 
```uri
https://anyview.link/embed/?img=<img url> 
https://anyview.link/embed/?img=<img url>&bg=<rgb>
```

Notes: 
* Image URL has to be `encodeURIComponent()` 
* background color is 6 characters RGB color, without the hash sign

Example:
```uri
https://anyview.link/embed/?img=https%3A%2F%2Fupload.wikimedia.org%2Fwikipedia%2Fcommons%2F1%2F1f%2FWikipedia_mini_globe_handheld.jpg&bg=000000
```

