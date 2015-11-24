# testing
one page test suite
--------------------

I used to make these pages for testing ideas, this was before codepen and sometimes I was offline and just needed to get the code on paper if you will.  The testing suites always grew out of hand though.  It would start with `jQuery` and a `google fonts` link. then I would add `PHP` to it and section out the `head` and `footer` to `PHP` includes to clean up the page since I added some `js` dependencies to play with and maybe a `CSS` reset or something.  Then it was lets put this on an online IDE so I have a server to serve the `PHP` then it was lets install `npm` and get `gulp` running to compile the `SCSS` files.  Oh a `linter` that's what it needs. Whoa, I took a simple test page and created a monster.

This is where **testing** comes into play.  It is a single `HTML` page with links to yes, some dependencies but I am keeping it to one single page I can copy paste into an editor or have a snippet in sublime text to create it on the fly, test what it was I wanted to test and be on my way. I have a similar setup in a [codepen template](http://codepen.io/danferth/) to test things but like I said sometimes our offline or just need to get it on paper and out of your head.

##Dependencies
####Loaded from [cdnjs](https://cdnjs.com/)
- ###Javascript
- jQuery 2.1.4
- angular 1.5.0
- angular-route 1.5.0
- angular-sanitize 1.5.0
- angular-animate 1.5.0
- foundation 6.0.1
- sweetalert 1.1.3
- waypoints 4.0.0
- TweenMax 1.18.0
- ###CSS
- font-awesome 4.4.0
- normalize 5.5.3
- animate 3.4.0
 
Yes, this is a lot of crap but you never know what you will need to get that awesome idea on paper *(er, screen)*.

The preloaded `js` snd `css` files may change as what I want to test will change. See the sublime text snippet to make this really fast to get up and going.
