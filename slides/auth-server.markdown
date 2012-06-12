#Auth - Server-Side Example

<pre class="brush: ruby">
require 'soundcloud'

# create client object with app credentials
client = Soundcloud.new(:client_id => 'YOUR_CLIENT_ID',
                        :client_secret => 'YOUR_CLIENT_SECRET',
                        :redirect_uri => 'REDIRECT_URL')

# redirect user to authorize URL
redirect_to client.authorize_url()
</pre>

[Documentation - Auth](http://dev.soundcloud.com/docs#authentication)
