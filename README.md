# webDevBootcamp
You know that presentation you're looking at, right now? These are the exercises associated with it.

Fork this repository so you can push the answers to the exercises. You will be turning in the finished repo to Professor Crow, along with a screenshot of your completed 90s personal website. 

## To serve the pages

For Python 2: ```python -m SimpleHTTPServer 8081``` in the root directory of your forked github repo. 

For Python 3: ```python -m http.server 8081``` in the root directory of your forked github repo. 

If you point your browser directly to http://localhost:8081, it you will see all the different directories listed. 

To serve up the first exercise, for example, browse to http://localhost:8080/Section1_HTML/test.html

## Section1_HTML

Normal Exercises:

1. test.html: Notice how the HTML is interpreted and structured by the browser. What you will see is the "default" styling. It's not pretty, but that's not the goal of HTML. HTML defines the text content and the hierarchy of information.

2. broken.html: The same HTML as test.html, but I've gone and broken things. As you can see, it doesn't render anymore. Compare the two files, and fix the broken one.

Advanced Exercises:

1. We've introduced quite a few different tags in the presentation. Try adding elements in order to add more content to the fixed HTML.

## Section2_CSS

### Reminder:
A valid CSS tag looks like this:
```css
selector {
	property: value;
	property: value1 value2 value3;
}
```

You can select by tag name (`div`), by class name (`.form-group`), or by ID (`#mpgPlot`)

### Questions

1. Your boss Gary comes in, having just read a clickbait article about "Millenial Pink". He is convinced that pink is in, and every data science product **must have a pink background, including your shiny app.** Your company's graphic designer Xiaotai, who has good taste but is powerless in the face of your boss's feverish cries for color, has made the best of a bad situation and recommended a specific pink shade to use: `#FFD6DC`. Of course, you are able to pick your own shade of pink (or even just use the color `pink`), but you have to *go pink or go home*. **Make your "shiny app" have a pink background.**


2. You change your background and are unsatisfied with how your graph looks now - just an ugly white box in a sea of pink. You see what the form box on the left looks like and you want something like that - with a white background and rounded corners. **Put the graph and its header in a white (or off-white: `#f5f5f5`) box with rounded corners.**
	
(Hint: I never told you how to do rounded corners in CSS. You gotta figure this out on your own, but it's not very difficult and can be done in one property.)

3. In what she will later explain to your company's HR department as a "heated designing moment", your web designer sent a number of very threatening emails to your boss over his use of the color pink. But things are still cool between you and her. However, she suggests that the font could use some revamping from Bootstrap's default font. **She suggests first changing the font of the form labels to something else... maybe try a serif font, like Georgia.**

4. Your phone buzzes. Your fellow data scientist Lydia, with whom you have spent an inordinate amount of time on this shiny app, just sent you some desperate messages on Slack. Apparently, the "show outliers" checkbox doesn't actually work, and there is no time to change the spaghetti code of your R app. Instead, you could try doing this in CSS. **Hide the "Show Outliers" checkbox using CSS.**

### More Fun

5. Both you and your web designer Xiaotai look at the font changes and are not satisfied. She suggests **grabbing a font from [Google Fonts](https://fonts.google.com) and using it instead of Georgia.**

6. Your boss, back after the Intentional Infliction of Emotional Distress lawsuit between him and your web designer was settled out of court for an undisclosed sum, has another brilliant idea to **spice up your shiny dashboard with some icons**.

(See the Bootstrap documentation on how to add icons in.)

### Really? You're done everything else? Okay, fine, here's some big brain CSS exercises.

1. After drinking a possibly unhealthy amount of mid-grade Panamanian coffee, your coworker Michael came up with the idea of adding in animations to spice up your dashboard even further.

* Make the form on the left hand side zoom in with an animation.

2. Mike and you agree that this looks a bit garish. instead, how about having the form box fade in?

3. Seriously? Okay. Have it so that...

 * The sidebar is initially invisible and the main panel takes up the entire width of the screen...

 * Then, the main panel resizes to how big it is normally (66% width?)

 * *Then*, the form box fades in.

## Section3_JS

Section 3 has two exercises that require you to write JavaScript functions. For exercise1.html, we've written a skeleton of the function with

//Your code here!

Marking where you need to fill in logic. 

exercise2.html requires you to fill out your own function completely.

When done, when you load the HTML into the browser the website will read EXERCISE COMPLETED in big letters if you finished. 

## Section4_PersonalWebsite

As with all labs, it's time to have a putting it-all-together section.

Requirements:
1. Must have HTML.
2. Must have custom CSS operating on those elements.
3. Must use D3 to create 3 or more custom text elements (h1, p, whatever you have)

Beyond that?

Go wild! You learned a lot of stuff today, so just see what you can do. Link to other HTML pages, add custom images.

At the end, screenshot it for Professor Crow and send that screenshot along with the repo link. 
