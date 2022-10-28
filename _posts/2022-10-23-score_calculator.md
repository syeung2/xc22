# Score Calculator

<script>
var clicksDN = 0;
var clicksMC = 0;
var clicksPO = 0;
var clicksRB = 0;
var clicksSM = 0;
var clicksWV = 0;
var countDN = 0;
var countMC = 0;
var countPO = 0;
var countRB = 0;
var countSM = 0;
var countWV = 0;
var counter = 1;
function onClickDN() {
  clicksDN += counter;
  if (countDN < 7){
    counter +=1;
  }
  if (countDN < 5){
    document.getElementById("clicksDN").innerHTML = clicksDN;
  }
  countDN +=1;
  document.getElementById("countDN").innerHTML = countDN;
};
function onClickMC() {
  clicksMC += counter;
  if (countMC < 7){
    counter +=1;
  }
  if (countMC < 5){
    document.getElementById("clicksMC").innerHTML = clicksMC;
  }
  countMC +=1;
  document.getElementById("countMC").innerHTML = countMC;
};
function onClickPO() {
  clicksPO += counter;
  if (countPO < 7){
    counter +=1;
  }
  if (countPO < 5){
  document.getElementById("clicksPO").innerHTML = clicksPO;
  }
  countPO +=1;
  document.getElementById("countPO").innerHTML = countPO;
};
function onClickRB() {
  clicksRB += counter;
  if (countRB < 7){
    counter +=1;
  }
  if (countRB < 5){
  document.getElementById("clicksRB").innerHTML = clicksRB;
  }
  countRB +=1;
  document.getElementById("countRB").innerHTML = countRB;
};
function onClickSM() {
  clicksSM += counter;
  if (countSM < 7){
    counter +=1;
  }
  if (countSM < 5){
  document.getElementById("clicksSM").innerHTML = clicksSM;
  }
  countSM +=1;
  document.getElementById("countSM").innerHTML = countSM;
};
function onClickWV() {
  clicksWV += counter;
  if (countWV < 7){
    counter +=1;
  }
  if (countWV < 5){
  document.getElementById("clicksWV").innerHTML = clicksWV;
  }
  countWV +=1;
  document.getElementById("countWV").innerHTML = countWV;
};
</script>

<button type="button" onClick="onClickDN()">Del Norte</button>
<p>Score: <a id="clicksDN">0</a>  Count: <a id="countDN">0</a></p>

<button type="button" onClick="onClickMC()">Mt Carmel</button>
<p>Score: <a id="clicksMC">0</a>  Count: <a id="countMC">0</a></p>

<button type="button" onClick="onClickPO()">Poway</button>
<p>Score: <a id="clicksPO">0</a>  Count: <a id="countPO">0</a></p>

<button type="button" onClick="onClickRB()">Rancho Bernardo</button>
<p>Score: <a id="clicksRB">0</a>  Count: <a id="countRB">0</a></p>

<button type="button" onClick="onClickSM()">San Marcos</button>
<p>Score: <a id="clicksSM">0</a>  Count: <a id="countSM">0</a></p>

<button type="button" onClick="onClickWV()">Westview</button>
<p>Score: <a id="clicksWV">0</a>  Count: <a id="countWV">0</a></p>