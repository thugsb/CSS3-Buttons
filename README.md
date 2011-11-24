## Just some other awesome CSS3 buttons

Whether you’re designing a website or a web application, you’ll need buttons for it. Now, with CSS3′s help, it was never easier to create nice looking buttons.

<div id="author-info">
  <div id="author-bio">
    <h4>
      Written by <a rel="external" title="Visit Red’s website" href="http://www.red-team-design.com">Red</a>
    </h4>
    
    <p>
      Catalin Rosu, a.k.a Red, is a professional web designer and developer who loves to be creative and enjoys CSS techniques. Stay tuned for latest updates, <a href="http://feeds.feedburner.com/redteamdesign"><b>subscribe to RSS</b></a> and <a href="http://www.twitter.com/catalinred"><b>follow him on Twitter</b></a>.
    </p>
  </div>
  
  <p>
    The CSS has been copied to github without the author's permission, in order to create a backup and allow branching for colour themes and additions.
  </p>
</div>

In order to create the icons, this set of CSS3 buttons uses [HTML entities][1].

### Why use entities rather than images?

*   Faster loading, because we’re talking about text here.
*   Scalable, depending on font size.
*   Styles as color and background are easy to update via CSS.

#### Rendering & browsers support

The icons are added using the `:before` [pseudo-element][2]. Therefore, you won’t see any icons in browsers like IE7 and below, but the buttons will look good yet.

### Minimal markup

<pre>&lt;a href="" class="button"&gt;Button&lt;/a&gt;
  </pre>

*Simple button, with no icon.*

<pre>&lt;a href="" class="button add"&gt;Add&lt;/a&gt;
  </pre>

*Note the `add` class adds the plus icon.*

<div id="buttonContainer">
  <h2>
    Actions
  </h2>
  
  <a href="" class="button">Button</a> <a href="" class="button add">Add</a> <a href="" class="button edit">Edit</a> <a href="" class="button delete">Delete</a> <a href="" class="button save">Save</a> <a href="" class="button email">Send email</a> <br /><br /> <h2>
    Miscellaneous
  </h2>
  
  <a href="" class="button like">Like</a> <a href="" class="button next">Next</a> <a href="" class="button star">Favourite</a> <a href="" class="button spark">Spark</a> <a href="" class="button play">Play</a> <br /><br /> <h2>
    Social media buttons
  </h2>
  
  <a href="http://twitter.com/catalinred" class="button tw">Follow me</a> <a href="http://www.facebook.com/RedTeamDesign" class="button fb">Become a fan</a> <h2>
    Buttons and inputs
  </h2>
  
  <button class="button">Clean button</button> <button class="button save">Button with icon</button> <button class="button" disabled>Disabled button</button> <button class="button save" disabled>Another disabled button</button> <br /> <input class="button" type="submit" value="Input submit" /> <input class="button" type="button" value="Input button" /> <input class="button" type="submit" value="Input submit disabled" disabled /> <input class="button" type="button" value="Input button disabled" disabled /> <br /><br />
</div>

Go to the [article][3]

 [1]: http://en.wikipedia.org/wiki/Html_entity
 [2]: http://www.red-team-design.com/before-after-pseudo-elements "The :before and :after pseudo-elements syntax"
 [3]: http://www.red-team-design.com/just-another-awesome-css3-buttons