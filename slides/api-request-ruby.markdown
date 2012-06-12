#API Request - Ruby

<pre class="brush: ruby">
require 'soundcloud'

# create a client object with your app credentials
client = Soundcloud.new(:client_id => 'YOUR_CLIENT_ID')

# find all tracks with the genre 'punk' that have a tempo greater than 120 bpm.
tracks = client.get('/tracks', :genres => 'punk', :bpm => {
  :from => 120
})
</pre>

<div class="sc_logo"></div>
