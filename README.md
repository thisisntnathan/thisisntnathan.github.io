# My personal website

A website for Nathan Lui.

# My changes to Forty

- Updated icon support to font-awesome v5.15 from the included v4.6 (`_sass/scss/`, `assets/webfonts/`, `assets/css/main.scss` )  
- Minimized footer (`footer.html`)  
  - Removed phone number  
  - Removed contact from  
  - Placed address and icons in same row  
- Swapped list <ul> with alternative list style <ul alt> (done rather sloppily, watch out for spacing issues...) (`_sass/components/_list.scss`)  
- Removed date from posts (better formatting available inside post content) (`allposts.html`)  
- Add $\LaTeX$ support by MathJax (`head.html`)
- If there are an odd number of tiles on the home page the theme now stretches the last one to fill the row (`_sass/components/_tiles.scss`)
- Removed extra slash (`/`) in homepage (`header.html`)

# Credits

Built off of a Jekyll version of the "Forty" theme by [HTML5 UP](https://html5up.net/) made by [Andrew Banchich](https://github.com/andrewbanchich/forty-jekyll-theme) both licensed under [Creative Commons Attribution 3.0 Unported](https://creativecommons.org/licenses/by/3.0/legalcode).  

[Jekyll](http://jekyllrb.com/) licensed under an [MIT License](https://github.com/jekyll/jekyll/blob/master/LICENSE).  
