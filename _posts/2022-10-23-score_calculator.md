# Score Calculator

<script>
var clicks = 0;
var counter = 1;
function onClick() {
  clicks += counter;
  counter +=1;
  document.getElementById("clicks").innerHTML = clicks;
};
</script>

<button type="button" onClick="onClick()">Del Norte</button>
<p>Score: <a id="clicks">0</a></p>

<button type="button" onClick="onClick()">Mt Carmel</button>
<p>Score: <a id="clicks">0</a></p>

<button type="button" onClick="onClick()">Poway</button>
<p>Score: <a id="clicks">0</a></p>

<button type="button" onClick="onClick()">Rancho Bernardo</button>
<p>Score: <a id="clicks">0</a></p>

<button type="button" onClick="onClick()">San Marcos</button>
<p>Score: <a id="clicks">0</a></p>

<button type="button" onClick="onClick()">Westview</button>
<p>Score: <a id="clicks">0</a></p>