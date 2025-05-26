---
layout: default
title:  Joe's Public Internet history
---

My web history is public. 

It's updated every hour or so when my machine is running. It goes back to about 2019 but I need to check that some truncation isn't happening at the bottom. 


You can see the code I use <a href="https://github.com/joereddington/export-history">on github</a>, and there's <a href="https://joereddington.github.io/2018/12/12/Internet.html"> a blog post that talks about the reasons</a>.


## Cool chart
The script that publishes my web history also creates the chart below.  It shows my 'web window' for the last few days. The large bars on the chart show the time between the first history entry of the day and the last.  In general I try and make these quite small - In the mornings I try to wait until I have a real need (or a list) of things to look up on the web and in the early evenings I try to properly switch off at the end of work. It also helps me from spend the weekend being present with the family.   

When making the 'web window' I don't count a number of sites. At the moment that's: Google Calendar, Google Drive and Zoom.  That means I can get quite a lot of work done before going 'properly' onto the internet. 

<IMG SRC="slots.png" alt="Chart Showing the times I used the internet" width=400>

<style>

ul {
list-style: none;
}
ul>li {
/* Most of this from https://dev.to/peterc/how-to-create-joined-bulletpoint-lists-with-css-bbc-news-style-1eem */
  /* You need to turn on relative positioning so the line is placed relative to the item rather than absolutely on the page */
  position: relative;

  /* Use padding to space things out rather than margins as the line would get broken up otherwise */
  margin: 0;
  padding-bottom: 1em;
  padding-left: 20px;
}

ul>li.same:before {
  background-color: #c00;
  width: 2px;
  content: '';
  position: absolute;
  top: -1.7em;
  bottom: 0px;
  left: 5px;
  height:2.4em;
}

ul>li:first-child:before {
  background-color: white;
}

ul>li::after {
  content: '';
  position: absolute;
  background-image: url("data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' aria-hidden='true' viewBox='0 0 32 32' focusable='false'%3E%3Ccircle stroke='none' fill='%23c00' cx='16' cy='16' r='10'%3E%3C/circle%3E%3C/svg%3E");
  background-repeat: no-repeat;
  background-size: contain;
  left: 0;
  top: 2px;
  width: 12px;
  height: 12px;
}

</style>



