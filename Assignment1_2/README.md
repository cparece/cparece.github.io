# cparece.github.io
Your name: 
<b>Cortney Stauffer (Parece)</b>

1. Provide a link to the first page of your website:  <a href="https://cparece.github.io/">https://cparece.github.io/</a>
View this document on github: <a href="https://github.com/cparece/cparece.github.io/blob/master/README.md"> README.md </a>

My site looks the way I want on (choose one): Mac 

With this browser (choose one): Chrome 

PART 1: RWD 2.0 WEBSITE (50 points)

1. Indicate 2 custom properties whose values change with media queries.

OUTSIDE THE MQ
Sass partial file name: _layout-new.scss
a. Line number for variable #1: 15 --width
b. Line number for variable #2: 13 --column

INSIDE THE MQ
Sass partial file name:
a. Line number for variable #1: 97 --width
b. Line number for variable #2: 139 --column

2. At least one occurence of calc
Sass partial file name:  _layout-new.scss
Line number: 16 

3. At least 1 media query not using width, min-width, or max-width
Sass partial file name: _layout-new.scss
Line number: 136

WARNING: while you may not document EVERY instance of custom properties and calc, we expect to see SEVERAL instances in your code.

We expect at least 1 media query.

We expect good Sass integration, using principles described in class.

Use semantic HTML, a mix of CSS selectors, and valid HTML and CSS.

We expect you to follow RWD 2.0 principles as discussed in class.



PART 2: Flexbox problem set (24 points)
4. URL for your Codepen or JSFiddle answer: https://jsfiddle.net/cparece12/skq5dwjn/



PART 3: TYPOGRAPHY  (25 points)
Part A: Font choices

5. Which fonts did you choose?
Font name #1: Abril Fatface
Font name #2: Open Sans
(list any additional if needed)

6. What type of font are you using (Oldstyle, Modern, etc)?
Font #1: Didonde Serif, it's a bold display font with thin serifs, and clean curves used for header style text.
Font #2: Sans Serif font that has a fairly neutral appearance and is optimized for readability on mobile and web devices.
(list additional if needed)

7. What type of relationship do you have between your fonts? Why does it work?
I wanted a contrasting appearance between my two fonts in weight and style. Having a readable font for the body text was key, so I went with something very simplistic (Open Sans), which allows contrast between my bold choice of header font (Abril FatFace).

Part B: Responsive typography and type scales
8. What is the name of the type scale used outside the media query?

In the first project, I created my own type scale with a base of 14px then converted to rems. I decided to adjust my already designs scale to follow what I had learned in Week 8. 

With what I had learnt, I cahnged my base to 16px and tried out a Major Second Scale (1.125). I originally was adding the rem scale number to the size, I realized I should be multiplying so I added in a multiply calc. 

Where did you get this scale from? (URL) https://medium.com/sketch-app-sources/exploring-responsive-type-scales-cf1da541be54

9. What changes did you make to the type scale inside the media query? (Describe the changes in English.)

I decided to just alter the base font size from 16px down by 2px for each media query. Since I am using rem's everywhere else, it scales nicely when looking at differnet breakpoints with both the font size and line height.

10. Identify the variables used in the type scale, where those variables are used outside the media query, and where the variable(s) change inside the media query. (This does not need to be exhaustive - identify 1 or 2 variables and trace them through your code.)

I uses scss variables for my type scale (since I had already started working with scss variables for font sizes) and started to use that as a proof of concept, once I was comfortable with changing the sizes in scss, I then tried out changing the sizes using custom css variables.


Sass partial file name: _css_variables.scss
Line number(s) where variables are defined and variable name(s):  3-12

Where were the variable(s) used outside the media query?
Partial file name (if different): _typography.scss
Line number(s): 9, 18, 31 

Where did the variable(s) value(s) change inside the media query?
Partial file name (if different): _typography.scss
Line number(s): 10-15, 19-24, 34-39




ABOVE AND BEYOND (11 POINTS)
Identify what you did for Above and Beyond. Provide any relevant HTML, CSS, or Sass line number(s) and explanation of what you did. How many points do you think this was worth, and why?

SUGGESTED: Integrate all of your layout and typography with similar variables. In other words, in the media queries, change the values of as few variables as possible to modify column layouts, padding, margin, and type scale.

I decided to test out a few pages converting my scss to variables. I created a new _css_variables.scss file to separate out the variables that I was converting.
The pages I had converted include: _overview.scss, _new_layout.scss, _typography.scss

I converted things like padding, margin, fonts, styles, etc. I did not convert the colors because a lot of my color logic depends on the mixins that I had previously created. But the css variables and scss variables seemlessly interact with one another
