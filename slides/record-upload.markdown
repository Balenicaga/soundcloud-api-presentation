#Record and Upload in your Browser

<pre class="brush: js, html">
SC.connect(function() {
  SC.record({
    start: function() {
      window.setTimeout(function() {
        SC.recordStop();
        SC.recordUpload({
          track: { title: 'This is my sound' }
        });
      }, 5000);
    }
  }
});
</pre>

<div class="sc_logo"></div>
