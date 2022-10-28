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
  clicksDN += counter;
  counter +=1;
  document.getElementById("clicksDN").innerHTML = clicksDN;
};
function onClickMC() {
  clicksMC += counter;
  counter +=1;
  document.getElementById("clicksMC").innerHTML = clicksMC;
};
function onClickPO() {
  clicksPO += counter;
  counter +=1;
  document.getElementById("clicksPO").innerHTML = clicksPO;
};
function onClickRB() {
  clicksRB += counter;
  counter +=1;
  document.getElementById("clicksRB").innerHTML = clicksRB;
};
function onClickSM() {
  clicksSM += counter;
  counter +=1;
  document.getElementById("clicksSM").innerHTML = clicksSM;
};
function onClickWV() {
  clicksWV += counter;
  counter +=1;
  document.getElementById("clicksWV").innerHTML = clicksWV;
};
</script>

<button type="button" onClick="onClickDN()">Del Norte</button>
<p>Score: <a id="clicksDN">0</a>Count: <a id="countDN">0</a></p>

<button type="button" onClick="onClickMC()">Mt Carmel</button>
<p>Score: <a id="clicksMC">0</a>Count: <a id="countMC">0</a></p>

<button type="button" onClick="onClickPO()">Poway</button>
<p>Score: <a id="clicksPO">0</a>Count: <a id="countPO">0</a></p>

<button type="button" onClick="onClickRB()">Rancho Bernardo</button>
<p>Score: <a id="clicksRB">0</a>Count: <a id="countRB">0</a></p>

<button type="button" onClick="onClickSM()">San Marcos</button>
<p>Score: <a id="clicksSM">0</a>Count: <a id="countSM">0</a></p>

<button type="button" onClick="onClickWV()">Westview</button>
<p>Score: <a id="clicksWV">0</a>Count: <a id="countWV">0</a></p>