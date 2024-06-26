<h1>OG Details</h1>
<p>This module will give you the ability to add/overwrite OG informations on pages, blog listing and blog posts.</p>
<p>Since the module is written  completly on vanilla Hubl no further scripts or add-ons are required. This is done on purpose for best possible performance and compability</p>
<h2>"Installation"</h2>
<p><i><strong>I recommend</strong></i> to put it as high as possible in module order in your templates as possible for best user experience since if you put it as the first module in your template it will be the first when the user opens the "Content"-Tab in the page editor</p>
<h3>Themes</h3>
<p><strong>Adding this module globally into every Page</strong></p>
<p>If you're working with themes - open the design-tools, find your theme, open the base.html, layout.html or similar and place the module snippet into it.
</p>
<p>&nbsp;</p>
<p><strong>In specific templates</strong></p>
<p>Open your desired template.html in the design-tools and place the module snippet anywhere you like. </p>
<h3>Templates (the old drag&drop inside the design-tools)</h3>
<p>Drag&drop this module into your template - as always: the position is up to you.</p>
<h2>Tipps for best usage</h2>
<p>I recommend to place the module at the highest possible place in your template so it will be shown at the top in the "Content"-Tab on your page/post for the page-creator.</p>
<p></p>
<h3>Important note</h3>
<p>As mentioned, the module requires jQuery to work. If you don't have jQuery activated in your Hub settings, theme or template you can activate the current, slim and minified version of jQuery directly in the module by clicking on the "enable jQuery" switch. <strong>If you're already using jQuery - don't activate it since this might break stuff and could lead to a negative impact on your page speed! If you're unsure if you're using jQuery(in most cases you do) ask a developer or inspect one of your pages that are live<sup>1</sup>.</strong>

<h2>Options</h2>
<ul>
<li>OG title(text) - set the title of your page/post. If empty it will be populated with your Page name</li>
<li>OG description(text) - set the description of your page/post. If empty it will be populated with the Meta description. It's limited to 200 characters</li>
<li>OG site name(text) - set the name of your site. If empty it will be populated with your company name.</li>
<li>OG image source(choice) - select if you want to use the featured image set in the settings of your page/post or a custom image</li>
<li>OG image(image) - if you select the custom image option in "OG image source" you will have the option to upload/select a custom image for this page/post. <strong>No image will be set automatically</strong></li>
<li>OG image(featured image) - <strong>No visible options in the module!</strong> This option will populate <code>og:image</code> and <code>og:image:alt</code> with informations set in the site/post settings.</li>
<li>OG image alt(text) - set the alt-text of the image. Will be populated with the alt-tag of the image</li>
<li>OG image width(text) - set the width of the image. Will be populated with the width of the custom image. <strong>Due to technical reasons the featured image option doesn't provide this option</strong></li>
<li>OG image height(text) - set the height of the image. Will be populated with the height of the custom image. <strong>Due to technical reasons the featured image option doesn't provide this option</strong></li>
<li>OG url(text) - set the url of your page/post. If empty it will be populated with the url of your page/post</li>
<li>OG Type:
Select what's the page about. You have all available Open graph options with all possible informations
<ul>
<li>Website (will be set by default)</li>
<li>Article</li>
<li>Book</li>
<li>Music / Song</li>
<li>Music / Album</li>
<li>Music / Playlist</li>
<li>Music / Radio station</li>
<li>Video / Movie</li>
<li>Video / TV show</li>
<li>Video / Episode</li>
<li>Video / Other</li>
</ul>
</li>
</ul>

<h2>Note for non developers</h2>
<ol>
    <li><strong>The design tools are a special function mostly for developers. You can find them by navigating to Marketing&nbsp;>&nbsp;Files&nbsp;&and;&nbsp;Templates&nbsp;>&nbsp;Design-Tools. If you don't see them please contact a developer or your site admin and let them set up this module for you</strong></li>
    <li>The recommended image aspect ratio is 1.91:1 (or simply 2:1). E.g. An image with 600px width and 300px height works fine</li>
    <li>For SEO and accessiblity reasons I always recommend to give a proper alt-text to an image.<br>Good alt-text: "New Macbook Pro is standing on the table".<br>Ok alt-text(image name): "new_macbook_pro-is_standing-on-the-table"<br>Bad alt-text: "img-1234567890.png"</li>
    <li>The OG image width and height are only used if you select the custom image option in "OG image source"</li>
    <li>If you haven't already set a company name, navigate to <br>Settings&nbsp;>&nbsp;Marketing&nbsp;>&nbsp;Email&nbsp;>&nbsp;Configuration&nbsp;>&nbsp;Footer</li>
</ol>
