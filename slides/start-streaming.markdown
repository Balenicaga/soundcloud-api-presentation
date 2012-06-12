#Start Streaming

<pre class="brush: js, html">
// initialize

SC.whenStreamingReady(function(){
  SC.stream("/tracks/293", function(sound){
    sound.play();
  });
});
</pre>

Can also pass options to SC.stream with an ontimedcomments callback

[SoundManager2 Docs](http://www.schillmania.com/projects/soundmanager2/doc/)

<div class="sc_logo"></div>
