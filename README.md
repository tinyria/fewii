### Resources
<ul>
  <li>Made with <a href="https://getbootstrap.com/" target="_blank">Bootstrap 5</a></li>
  <li>Cherry icon used for the button is from <a href="https://www.flaticon.com/" target="_blank">Flaticon</a></li>
  <li>Fonts are sourced from <A href="https://fonts.google.com/" target="_blank">Google Fonts</a>. All other icons are from <a href="https://icons.getbootstrap.com/" target="_blank">Bootstrap</a></li>
  <li><a href=https://favicons.joshuasoileau.com/" target="_blank">Turn emojis into favicons!</a></li>
</ul>

<p>If you're looking for the FE3H skill icons I have — they're originally from the Spriter's Resource, but I edited them to match the in-game sprites. Feel free to use them if you want!</p>

### Extra stuff
<p>I'm not well-versed in Javascript, so any scripts used/mentioned/included are written with the help of ChatGPT.</p>
<br>
<ul>
  <li>Name Swap Button</li>
  <ul>
    <li>Utilizes Javascript to change span's marked with a custom class.</li>
  </ul>
  <li>Masonry with Bootstrap 5 Tabs</li>
  <ul>
    <li>As it turns out, Masonry will only initialize properly when the tab using Masonry has an .active class or is the starting tab of your website. You can work around this though by writing a Javascript code that tells Masonry to re-initalize when the associated tab is opened.</li>
  </ul>
  <li>Checkbox filtering with Bootstrap 5 cards and Masonry</li>
    <ul>
      <li>Initially, I was planning on using HTML/CSS checkbox filtering with the use of data-filters — so I use data-filters to tag my cards appropiately. I use Javascript to sort the cards and re-initalize Masonry when the cards are filtered. A weird issue I had was that some of the filters would force all of the cards into one column, when on MD devices I have Bootstrap set to 2 columns and 3 columns for LG devices. This can be fixed by telling Masonry to force everything into the correct number of columns with Javascript.</li>
      <li>If you want OR filtering (what I use filters with AND, I think), this <a href="https://github.com/dynamick/multiple-filter-masonry/blob/master/multipleFilterMasonry.js" target="_blank">code</a> seemed pretty good!</li>
    </ul>
  <li>Transforming a sidebar to a top bar navigation on mobile or SM devices</li>
  <ul>
    <li>Bootstrap responsive flex behavior works really nicely for this one. You could PROBABLY set it to transform into a hamburger menu if you wanted to, but I just got lazy...</li>
  </ul>
</ul>
