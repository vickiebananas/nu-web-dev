---
title: 'Unit 4 Lab'
layout: post
ordering: 4
unit: 4
---

This assignment will have you practice using JavaScript to make your sites interactive. Make sure to refer to the unit readings for helpful reference material as well as additional resources. 

### Description
Choose 2 interactive features to add to your site. You may come up with your own or choose from some of the options below:
- Add a Font Size Adjuster that allows users to increase and decrease the size of the font on your site
- Add a Font Type Adjuster that allows users to change the font on your site (e.g., serif, sans-serif)
- Add a Theme Switcher that allows users to change the color schemes on your site (e.g., light mode, dark mode, high contrast mode)
- Add some effects for your images (e.g., enlarging on click, caption on hover)

Of course, it's imperative that we ensure our site continues to be accessible as we add new/more features and change our code. Perform some basic accessibility testing using your browsers' built-in dev tools (refer to [Unit 2 readings]({{site.baseurl}}/units/unit2/#developer-tools) as needed) and any of our posted [accessibility testing resources]({{site.baseurl}}/accessibility-resources#accessibility-testing). 

At a minimum, your site should:
- Be keyboard-only navigable including:
	1. All buttons, links, and inputs are can be selected (reached) without a mouse (i.e., via tabbing)
	1. Any element currently selected (in-focus) is perceivably different (e.g., underlined or boxed)
	1. All buttons, links, and inputs are can be activated (clicked) without a mouse
	1. There are no 'keyboard traps'
- Be screen-reader friendly including
	1. Headings are used logically and with no skipped heading numbers
	1. All pages have accurate page titles and metadata
 	1. Code makes appropriate use of semantic HTML including use of `<nav>` and `<main>`, and others as applicable
  	1. `<div>`s and `<span>`s are used sparingly and only where semantic HTML wouldn't make sense
	1. All images have appropriate alt text
- Have sufficient contrast (applicable to all themes if that's one of the features you choose)
- Have an option to enable and disable any automatic animations
- Is usable with up to 400% magnification
- Is usable with stylesheets disabled
- Is usable with images disabled
- Is usable with JavaScript disabled
- Is usable across various browsers
- Is usable across various devices of various sizes

If you have any questions about what the above entail, please first refer to our posted [accessibility resources]({{site.baseurl}}/accessibility-resources)-- the [General Tips]({{site.baseurl}}/accessibility-resources#general-tips) section might be of particular use.

Additionally, you'll be submitting your code for review this week so please make sure your code is free of errors and that your site is complete.

### Recorded Lecture (coming soon)

### What to Submit
Create a short README text document in your site's root folder describing the interactive features you chose to implement and what their expected behaviour is. Zip/Compress this root folder, ensuring your site works as expeceted from the files in that folder alone, and submit it. Remember all submissions are done through Canvas. 

### Requirements
#### Submission
1. Site runs from files in zipped/compressed folder
1. All links and images work
1. Folder includes a README describing the interactive features implemented and their expected behaviour

#### Design and User Experience
1. Site has a good, cohesive design
1. Site is responsive and mobile-friendly including:
	- Is usable across various browsers
	- Is usable across various devices of various sizes
1. Site is dynamic: at least two interactive features are implemented and behave as expected/described
1. Site is accessible. At a minimum, site:
	1. Is keyboard-only navigable including:
		1. All buttons, links, and inputs are can be selected (reached) without a mouse (i.e., via tabbing)
		1. Any element currently selected (in-focus) is perceivably different (e.g., underlined or boxed)
		1. All buttons, links, and inputs are can be activated (clicked) without a mouse
		1. There are no 'keyboard traps'
	1. Is screen-reader friendly including:
		1. Headings are used logically and with no skipped heading numbers
		1. All pages have accurate page titles and metadata
  		1. Code makes appropriate use of semantic HTML including use of `<nav>` and `<main>`, and others as applicable
  		1. `<div>`s and `<span>`s are used sparingly and only where semantic HTML wouldn't make sense
		1. All images have appropriate alt text
	1. Has sufficient contrast (applicable to all themes if that's one of the features implemented)
	1. Has an option to enable and disable any automatic animations
	1. Is usable with up to 400% magnification
	1. Is usable with stylesheets disabled
	1. Is usable with images disabled
	1. Is usable with JavaScript disabled

#### Programming
1. HTML and CSS are free of syntax errors
1. JS (and JQ, if used) is free of syntax errors
1. JS (and JQ, if used) is used appropriately and efficiently
1. Browser console gives no errors
1. Browser console gives no warnings

#### Organization
1. CSS is in external stylesheet
1. JS is in external script
1. JQ, if used, is in external script 
1. Images are in their own folder
1. Scripts are in their own folder
