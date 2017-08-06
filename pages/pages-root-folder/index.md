---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage

widget1:
  title: "You'd love see your project hosted at RHoK?"
  url: "/submit"
  text: "Get in touch we're always searching for new challenges to RHoK!"

widget2:
  title: "RHoK Berlin #5<br/>from<br/>12th to 13th August"
  url: "/event"
  text: "You're curious about technologies or socio-economic challenges?<br/> You'd like to make the work a better place?<br/>Get up and joind us hackking for humanity!"

widget3:
  title: "Random Hacks of Kindness"
  url: "/about"
  text: "..are global hackathons facing pressing social challenges. We are a dynamic global community of innovators (hackers and makers) prototyping open technology to reveal solution approaches to actual problems."


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
  url: //participate/
  text: Participate! ›
  style: alert
permalink: /index.html


#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
