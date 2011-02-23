# Yaws #
Another Erlang web server, similar to Mochiweb

<div class="center">
<img src="images/apachevsyaws.jpg" style="max-width: 30%; width: 30%; "/>
</div>

Apache dies at ~4,000 concurrent reqs. Yaws still ticking up around *~80,000*. 

Total throughput does not decrease as load increases. 

Work done to get 1,000,000 concurrent requests *on a single box* with Mochiweb