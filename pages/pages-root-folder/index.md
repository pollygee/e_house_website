---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: food.jpg
widget1:
  title: "Soup Kitchen"
  url: 'http://github.com/pollygee/kitchen'
  image: food.jpg
  text: 'Dinner is served 6:00pm - 7:30pm each evening.  We are open for dinner every evening of the year except Thanksgiving (many organizations in the area serve a special meal on this day). Dinner clients are also given a lunch for the following day.  We serve around 45 people each evening.  Please join us!'  

widget2:
  title: "Food Pantry"
  url: 'http://github.com/pollygee/pantry'
  image: widget-1-302x182.jpg
  text: 'We make appointments Tuesdays, Thursday and Saturday mornings.  We provide USDA food to clients who live in PG county.  All Laurel residents recieve food from Elizabeth House from donations and groceries we purchase.  For more information and to find out if you qualify, please call <b>240-547-9013</b>'

widget3:
  title: "Bundles"
  url: 'https://github.com/pollyggee/bundles'
  image: widget-github-303x182.jpg
  text: '<em>Holiday Bundles</em> are distributed several times a year.  Usually around Thanksgiving Christmas and Fourth of July.  Check here for updated informtaion about upcoming bundles when we are accecpting RSVPs.'


#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/feeling-responsive
  text: Inform me about new updates and features ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
