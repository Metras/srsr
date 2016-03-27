
---

# SHOUTcast Radio Status/Request (SRSR) #

---

## VERSION: 1.0 ##

### LICENSE / CREDITS ###
  * Code by Damian Taggart, Mindshare Studios, 04/2009
  * GNU Public License v3, http://www.gnu.org/licenses/gpl-3.0.txt
  * Based on/inspired by PHP scripts from the following people:
> Henrik Malmberg, Dan Brown, Oddsock

### REQUIREMENTS ###
  * PHP 5 (with SimpleXML and cURL support)
  * You **MUST** setup your SHOUTcast server first! Make sure it works! Then install SRSR!

### INSTALL ###
  1. Save a copy of `config-default.php` as `config.php`
  1. Edit `config.php` with your SHOUTcast server settings
  1. Upload all files
  1. Visit `index.php` in your browser
  1. If you are using the song request feature, you have to generate a playlist in `.m3u` format and upload it to the installation directory

### CUSTOMIZATION ###
  * All visual files are in `theme` directory, along with the CSS

### INTRODUCTION ###
SRSR creates a dynamic web page for your SHOUTcast radio station from
your server's XML data and formats the info into a stat page, completely
customizable via CSS. The page is updated every 15 seconds via AJAX (no refresh).

### HELP/COMMENTS ###
  * Project page: http://www.mindsharestudios.com/downloads/srsr/
  * Post an issue on the issue tracker: http://code.google.com/p/srsr/issues/list
  * NO free support is guaranteed, I'll try, but no promises!