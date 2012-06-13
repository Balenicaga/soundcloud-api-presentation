# Auth - Client-Side Example

<pre class="brush: js, html">
  SC.connectForm({
    size:         "m", // size of the button (s, m, l)
    client_id:    "YOUR_CLIENT_ID",
    redirect_uri: "http://your-app/soundcloud-callback.html",
    connected: function(){
      // now do something interesting :)
    }
  });
</pre>

See [SoundCloud Connect](http://developers.soundcloud.com/docs/connect)

<div class="sc_logo"></div>
