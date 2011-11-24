# Just some other awesome CSS3 buttons

Whether you’re designing a website or a web application, you’ll need buttons for it. Now, with CSS3′s help, it was never easier to create nice looking buttons.

## <a href="http://www.red-team-design.com/wp-content/uploads/2011/09/awesome-css3-buttons.html">View demo</a>

#### Written by <a href="http://www.red-team-design.com">Red</a>

Catalin Rosu, a.k.a Red, is a professional web designer and developer who loves to be creative and enjoys CSS techniques. Stay tuned for latest updates, <a href="http://feeds.feedburner.com/redteamdesign"><b>subscribe to RSS</b></a> and <a href="http://www.twitter.com/catalinred"><b>follow him on Twitter</b></a>.

*The CSS has been copied to github without the author's permission, in order to create a backup and allow branching for colour themes and additions.*

In order to create the icons, this set of CSS3 buttons uses [HTML entities][1].

### Why use entities rather than images?

*   Faster loading, because we’re talking about text here.
*   Scalable, depending on font size.
*   Styles as color and background are easy to update via CSS.

### Minimal markup

<pre>&lt;a href="" class="button"&gt;Button&lt;/a&gt;</pre>

*Simple button, with no icon.*

<pre>&lt;a href="" class="button add"&gt;Add&lt;/a&gt;</pre>

*Note the `add` class adds the plus icon.*

#### Rendering & browsers support

The icons are added using the `:before` [pseudo-element][2]. Therefore, you won’t see any icons in browsers like IE7 and below, but the buttons will look good yet.

Go to the [article][3]

 [1]: http://en.wikipedia.org/wiki/Html_entity
 [2]: http://www.red-team-design.com/before-after-pseudo-elements "The :before and :after pseudo-elements syntax"
 [3]: http://www.red-team-design.com/just-another-awesome-css3-buttons