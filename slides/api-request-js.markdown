#API Request - JavaScript

<pre class="brush: js, html">
SC.initialize({
  client_id: 'YOUR_CLIENT_ID'
});

// find all tracks with the genre 'punk' that have a tempo greater than 120 bpm.
SC.get('/tracks', { genres: 'punk', bpm: { from: 120 } }, function(tracks) {
  console.log(tracks);
});
</pre>

<div class="sc_logo"></div>
