<h1>Sidebar Pokewalker</h1>
<p>A small static pokewalker made with html with changeable sprites for my neocities page.</p>
<h2>Installing</h2>
<p>Change the image file url for the route sprite (<code>Route_where.png</code>) and the pokemon sprite (<code>Spr_4pw_000</code>) for whichever sprite you want to display. You can find compatible sprites at <a href="https://archives.bulbagarden.net/wiki/Category:Pok%C3%A9walker_sprites">Bulbapedia</a></p>

<p>Include the following code somewhere in the "body" tag of where you want the pokewalker to show:</p>
<code> <iframe style="height:230px; width:230px;" scrolling="no" src="/pokewalker.html" title="pokewalker"></iframe> </code>
<br>
<br>
<p>Include the following code somewhere in the css file or "style" tag of your page:</p>
<code>iframe {
height: 230px;
overflow: hidden;
margin: auto;
}</code>
