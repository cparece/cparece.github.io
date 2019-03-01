# cparece.github.io
Your name: 
<b>Cortney Stauffer (Parece)</b>

1. Provide a link to the first page of your website: <a href="https://cparece.github.io/">https://cparece.github.io/</a>

My site looks the way I want on (choose one): <b>Mac</b>

With this browser (choose one): <b>Chrome </b>

PART 1: BASE RESPONSIVE WEBSITE (24 points)

1. I used <b> Flexbox and Grid </b> in making my responsive website.

2. Sass partial file name and line number where a media query appears:
<b> <a href="cparece.github.io/styles/_layout.scss"> layout.scss </a> </b>lines 8, 11, 14
<b> <a href="cparece.github.io/styles/_mixin.scss"> mixin.scss </a> </b>lines 1-14 (media query mixin)
<b> <a href="cparece.github.io/styles/_timeline.scss"> timeline.scss </a></b> lines 8, 12, 18
<b><a href="cparece.github.io/styles/_variables.scss"> variables.scss </a> </b> lines 55-57 (variables for breakpoints)

3. Cite your images here: All images are my own.

4. Certify you wrote your own content by typing an affirmative statement here: I wrote all my own content, based on my experience and love to travel! My website is based on my love to travel and thinking about how to solve the problem of organizing a lengthy vacation with several hotels, flights and activities.

PART 2: SASS (50 points)
Provide partial file name(s) and starting line number(s) for the comment in Sass for the start of each item.

5. Sass variable list: 
       <a href="cparece.github.io/styles/_variables.scss"> variables.scss </a> entire file
      

6. 1 custom-coded mixin:
       <a href="cparece.github.io/styles/_mixin.scss"> mixin.scss </a> entire file


7. 1 extend:
Extend for Flex:
       <a href="cparece.github.io/styles/_variables.scss"> variables.scss </a> lines 61-66
       <a href="cparece.github.io/styles/_overview.scss"> overview.scss </a> line 7
       <a href="cparece.github.io/styles/_navigation.scss"> navigation.scss </a> line 9
       <a href="cparece.github.io/styles/_layout.scss"> layout.scss </a> line 53
Extend for Img:
       <a href="cparece.github.io/styles/_variables.scss"> variables.scss </a> lines 40-46
       <a href="cparece.github.io/styles/_layout.scss"> layout.scss </a> line 37

8. 2 levels of nesting:
       <a href="cparece.github.io/styles/_navigation.scss"> navigation.scss </a> line 4, 10

9. 2 instances of built-in Sass functions:
       <a href="cparece.github.io/styles/_palette.scss"> palette.scss </a> most of palette file includes built in sass functions lighten($color, $amount), darken($color, $amount), hue($color), hsl($hue, $saturation), etc.

10. 1 use of if/else
       <a href="cparece.github.io/styles/_palette.scss"> palette.scss </a> lines 51-56
       <a href="cparece.github.io/styles/_mixin.scss"> mixin.scss </a> lines 72-84

11. The names of at least 2 partial files
       <a href="cparece.github.io/styles/_layout.scss"> layout.scss </a>
       <a href="cparece.github.io/styles/_mixin.scss"> mixin.scss </a>
       <a href="cparece.github.io/styles/_navigation.scss"> navigation.scss </a>
       <a href="cparece.github.io/styles/_overview.scss"> overview.scss </a>
       <a href="cparece.github.io/styles/_palette.scss"> palette.scss </a>
       <a href="cparece.github.io/styles/_timeline.scss"> timeline.scss </a>
       <a href="cparece.github.io/styles/_typography.scss"> typography.scss </a>
       <a href="cparece.github.io/styles/_variables.scss"> variables.scss </a>


PART 3: COLOR  (25 points)
Provide partial file name(s) and starting line number(s) for the comment in Sass for the start of each item.

11. Explain your color scheme. Did you use Natalya's work? Did you make modifications to it?
I did not use Natalya's work, I came up with my own <a href="cparece.github.io/styles/_palette.scss"> color palette </a>. I wanted the flexability to have 3 colors since I wanted my calendar to be driven based on 3 types of events (hotels, flights and activities). So I decided on a triad palette. Other than white, the only color that I hard coded was hsl(178, 76%, 37%) for my base color. from there I used the base color to calculate my accent and accent alternate. A triad palette is based off of changing th hue by 120 and 240, but keeping saturation and lightness the same. After compiling, I realized my triad color was a bit odd and didn't read the best, so I decided to tweak the lightness. Once I got these colors, I also decided to expand the palette to give me a variety of light and dark options for each color. I decided on 9 color variables for each accent. I then created a function that would allow me to easily make sure my text can be switched to light or dark depending on the background color.



ABOVE AND BEYOND (10 POINTS)
Identify what you did for Above and Beyond. Provide any relevant HTML, CSS, or Sass line number(s) and explanation of what you did. How many points do you think this was worth, and why?



