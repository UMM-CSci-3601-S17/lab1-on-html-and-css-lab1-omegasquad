# Lab Tasks
## Summary
Your task for this lab is to develop a static web page for a small business, such as a health food store, using HTML and CSS. Do not use any javascript. You may include forms if you'd like, but no form handling at this point.

All of the formatting (including the positioning of elements in the page) must be done using CSS. Do not include width, height, fonts, colors, etc into your HTML. Do not use absolute settings for sizes, make them relative to your page size and your default font. You are required to use some HTML5 and may use CSS3 features. If a feature is not supported in some browsers, please clearly indicate which browsers support it and which ones don't. 

## Technical Requirments:
Please read carefully the list of technical requirements below and follow it precisely.

  - Your page must use an **external CSS file**. You may, if needed, use inline CSS for more specific settings, but make sure to explain (in comments) why it's needed.
  - Your **HTML** and **CSS must validate** ([HTML validator](https://validator.w3.org/), and [CSS validator](https://jigsaw.w3.org/css-validator/)), except perhaps warnings about features not supported in all browsers.
  - Your page must look reasonable and be relatively easy to navigate: there should be no fonts that are hard to read, links that are hard to see, or unpleasant color combinations. While we will not be evaluating your design _per se_, we may take points off for features that lead to a problematic user experience.
  
> Protip: Fonts specified in CSS can be different in different browsers! Just because ``font-family: "Comic Sans"`` looks sweet in Internet Explorer 5 (which you better not be using) doesn't mean it will in Chrome or Firefox.

  - Your **page must look reasonable in all standard browsers** (recent Chrome, Firefox, Safari, IE, Edge) and preserve its setup when the window is resized.

> Protip: Making web pages that can resize across many different screen sizes and devices is referred to as _responsive web design_. This is a big thing right now. By using fancy styling, among other tools, to adjust how a web page looks, developers can make a single page rather than multiple for each type of device. To see how your page would look on some phones or tablets: open your page in Chrome > right-click the page > click "inspect element" > click the little phone symbol in the top-left corner. This will show roughly what your site would look like on the chosen device. 

  - Your page must have the **following elements implemented as div elements** (do not use tables for formatting; use CSS positioning, see [the links in the README](./README.md)):
    - A **navigation bar.** It must be a fixed percentage of the page and resize with the window. It may be horizontal or vertical.
    - A **footer** with the company's address, contact information, etc.
    - At least one more **div for the main part of the page**. Typically each div is marked with its own id, for CSS formatting. 
  - At least **three images**. Since we don't have a real business to develop the page for, just use any images as a mock-up. Make sure you abide by relevant copyrights; it's probably simplest if you search for images that have appropriate Creative Commons licenses. The quality of the images is not a part of the grade.

> Protip: If you're having trouble finding decent images for your site, remember that you can take pictures with your phone and use them. As long as no people or company logos are featured prominently, images should be safe to use.

  - You must use at least **12 elements** in your page. List items of the same list count as one element for this purpose.
  - You must use at least **10 CSS rules** in your CSS file (a rule is a selector followed by settings for this selector).
  - In your CSS you must use each of the following: **grouping, nesting, a class, and an id**.
  
> Protip: I'd recommend playing with grouping and nesting after you've already written a bit of CSS, it'll be easier to understand why it's so cool. A good explanation of grouping and nesting can be found [here](http://lmgtfy.com/?q=grouping+and+nesting+css&l=1). Also, you can see some general info on CSS selectors [here](http://www.w3schools.com/cssref/css_selectors.asp).

  - You must use at least two and **no more than five HTML5 features**.
  - You may use **no more than three CSS3 features.** 
