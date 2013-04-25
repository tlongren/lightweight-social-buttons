#Lightweight social share buttons

Let your users share your articles with no need of jQuery or Javascript.<br/>
Good for performance since only two request will be made.<br/>
Just simple anchor tags, some neat CSS and an icon font.<br/>
If you want to display the icons in older browsers (lt IE7) just include lte-ie7.js with a conditional HTML comment and you're good to go.<br/>
<a href="http://codepen.io/christian-fei/full/uemGF">PREVIEW</a>

##Preparation

Just copy the css folder in your project and reference the style.min.css file inside the head tag of your HTML file.

##The markup

If you want to show a button for facebook:<br/>
&lt;a href="#" class="button facebook"&gt;Share on &lt;span class="icon-facebook"&gt;&lt;/span&gt;&lt;/a&gt;<br/>
Where<br/>
a.button  			~ a reusable class, that simply resembles a button<br/>
a.facebook 			~ sets the color for the button, in this case FB-blue<br/>
span.icon-facebook 	~ displays the icon for this social network<br/>
[opt]<br/>
a.box 				~ drops a shadow behind the button<br/>

##URL-schemes

Just put this URL-scheme inside the href of the anchor tag:<br/>
FACEBOOK:<br/>
[http://www.facebook.com/sharer.php?u=[URL]](#)<br/>
TWITTER:<br/>
[http://twitter.com/home?status=Currently reading: [URL]](#)<br/>
GOOGLE PLUS:<br/>
[https://plus.google.com/share?url=[URL]](#)<br/>
PINTEREST<br/>
[http://pinterest.com/pin/create/button/?url=[URL]&amp;media=[MEDIA-URL]&amp;description=[DESCRIPTION]](#)<br/>

Where:<br/>
[URL] 			~ the URL you want to share<br/>
[MEDIA-URL] 	~ a link to an image<br/>
[DESCRIPTION] 	~ the description<br/>

##Icon font

The free service for creating the icon font is [icomoon.io](http://icomoon.io)

The license : [CC BY-SA 3.0](http://creativecommons.org/licenses/by-sa/3.0/)

The icon font is compatible with all major browser and with some JS magic, even the old IE6 can understand the font.


###Thanks

I would like to thank [Nate Vaughn](https://twitter.com/NateVaughn) for the heads up on the twitter intents thingy.
