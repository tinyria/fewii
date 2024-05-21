### resources
<ul>
  <li>made with <a href="https://getbootstrap.com/" target="_blank">Bootstrap 5</a></li>
  <li>cherry icon from <a href="https://www.flaticon.com/" target="_blank">Flaticon</a></li>
  <li>fonts from <A href="https://fonts.google.com/" target="_blank">Google Fonts</a></li>
  <li><a href=https://favicons.joshuasoileau.com/" target="_blank"turn emojis into favicons</a></li>
</ul>

<p>if you're looking for the FE3H skill icons i have, i found them from spriters resource then edited all of the files to look like the ingame ones. you probably don't want to do that by hand tho so feel free to just take the ones i already made :P</p>

### some stuff
<p>im still javascript stupid so i just talked to chatgpt for a really long time in order to get the scripts i needed for some of the javascript stuff here</p>
<br>
<ul>
  <li>name swap button</li>
  <ul>
    <li>a javascript function targetting a specific class to change the names -> i put a custom class on span tags and the javascript swaps the span whenever you click the button</li>
  </ul>
  <li>masonry with tabbable content in bootstrap 5</li>
  <ul>
    <li>masonry doen't initialize properly wiith bootstrap 5 local tabs UNLESS you make the tab with masonry active OR you make a script that initalizes the masonry only when that specific tab is opened</li>
  </ul>
  <li>checkbox filtering with masonry cards</li>
    <ul>
      <li>the javascript filters by AND and not OR based on data-filters i put on each card. i was gonna do some css/html checkbox filtering then i found out 1) this is hard 2) this probably doesn;t work with masonry. for some of the filters, you may get this thing where all the cards stack in one column even though you have a multiple column set up -> you just need a script that forces the cards into the appropriate amount of columns + to be safe tell masonry to initalize each time</li>
      <li>if you want OR filtering, this <a href="https://github.com/dynamick/multiple-filter-masonry/blob/master/multipleFilterMasonry.js" target="_blank">code</a> seemed pretty good</li>
    </ul>
  <li>converting a sidebar to a topbar on sm devices</li>
  <ul>
    <li>the answer you are looking for is responsive flex-columns.  you can switch the column to a row on small screen sizes and the nav will adjust accordingly 👍 i was actually hoping to have a hamburger menu pop up on top bar navigation, but that's a problem for another day ig. i didn't want to copy and paste unnecessary stuff so i'll ride or die with my single navbar!</li>
  </ul>
  <li>single footer at bottom of page throughout all tabs</li>
  <ul>
    <li>if your thing is similar to mine and your tabs don't have enough content to take up viewport height -> use calc() in styling to set the minimum height as the size of the viewport minus the footer -> your tabs will always be viewport height at minimum and the footer will stick to the bottom of each tab</li>
  </ul>
  <li>image goes flippy</li>
  <ul>
    <li>css animation styling. you can check out some stuff about it on <a href="https://www.w3schools.com/css/css3_animations.asp" target="_blank">w3 schools</a></li>
  </ul>
</ul>
