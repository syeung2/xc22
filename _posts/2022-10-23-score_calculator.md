# Score Calculator

<script>
var clicksDN = 0;
var clicksMC = 0;
var clicksPO = 0;
var clicksRB = 0;
var clicksSM = 0;
var clicksWV = 0;
var counter = 1;
function onClickDN() {
  clicks += counter;
  counter +=1;
  document.getElementById("clicksDN").innerHTML = clicks;
};
function onClickMC() {
  clicks += counter;
  counter +=1;
  document.getElementById("clicksMC").innerHTML = clicks;
};
function onClickPO() {
  clicks += counter;
  counter +=1;
  document.getElementById("clicksPO").innerHTML = clicks;
};
function onClickRB() {
  clicks += counter;
  counter +=1;
  document.getElementById("clicksRB").innerHTML = clicks;
};
function onClickSM() {
  clicks += counter;
  counter +=1;
  document.getElementById("clicksSM").innerHTML = clicks;
};
function onClickWV() {
  clicks += counter;
  counter +=1;
  document.getElementById("clicksWV").innerHTML = clicks;
};
</script>

<button type="button" onClick="onClickDN()">Del Norte</button>
<p>Score: <a id="clicksDN">0</a></p>

<button type="button" onClick="onClickMC()">Mt Carmel</button>
<p>Score: <a id="clicksMC">0</a></p>

<button type="button" onClick="onClickPO()">Poway</button>
<p>Score: <a id="clicksPO">0</a></p>

<button type="button" onClick="onClickRB()">Rancho Bernardo</button>
<p>Score: <a id="clicksRB">0</a></p>

<button type="button" onClick="onClickSM()">San Marcos</button>
<p>Score: <a id="clicksSM">0</a></p>

<button type="button" onClick="onClickWV()">Westview</button>
<p>Score: <a id="clicksWV">0</a></p>