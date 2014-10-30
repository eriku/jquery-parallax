# Element Parallax

I created a Parallax jQuery for a project I'm working on right now. All the one's I found online only worked for background images so in the typical developer way, I created my own.  

This coding will allow you to use either an image or video as the parallax background.

    <div id="hero" data-type="parallax" data-prlx-parent="true">
      <div class="parallax-background">
        <img class="image" src="http://thumbs.dreamstime.com/z/lavender-field-sunset-stunning-landscape-40631568.jpg" data-prlx-type="sprite" data-size="fullsize" data-prlx-speed="0.3">
      </div>
      <div class="hero-content" data-fadeout="true" data-prlx-type="sprite" data-prlx-speed="0.6">
        <h2>Here's a bunch of content that will fade out on scroll</h2>
      </div>
    </div>
    
## Demo
[http://parallax.erikuunila.com](http://parallax.erikuunila.com)