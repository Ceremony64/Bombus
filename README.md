# Bombus 🐝

This is the greatest addon to your website since the first 🐝 have graced the earth.


## How do I add this awesome shit?
It is easy!
1. Grab `🐝.js` and embed it:
   ```html
   <script src="🐝.js"></script>
   ```
2. Grab `🐝.css` and add it your existing CSS or embed it as a separate file:
   ```html
    <link rel="stylesheet" href="🐝.css">
   ```

3. Embed the `🐝.svg` directly into your document's body. Example:
   ```html
   <!DOCTYPE html>
   <html>
       <head>
           <title>My website</title>
           <script src="🐝.js"></script>
           <link rel="stylesheet" href="🐝.css"/>
           <!-- other header stuff -->
       </head>
       <body>
           <!-- page content -->
       </body>
   </html>
   ```
4. Call `bombus.summer()` to spawn all those lovely 🐝

See `example.html` for a proper example.

## Other stuff
- Set `bombus.path = 'folder/with/your/bombus/` to set the path to the bombus folder. Don't forget the trailing slash! Default is `bombus/`
- Set `bombus.extension = 'svg` to overwrite the file type to svg (costly animation! not recommended!). Default is `png`
- Call `bombus.summer(10)` to spawn exactly 10 🐝. Call it again and again until your browser crashes. Definitely worth it!
- Call `bombus.winter()` to remove all the cute little 🐝. **YOU \*\*\*\*ING MURDERER!**
- Call `bombus.bps(120)` to set the update rate of the 🐝 to 120. (bps stands for 🐝 per second). You are limited by the current monitors freshrate tho. Default is 60bps

## License
[CC BY](https://creativecommons.org/licenses/by/4.0/)
