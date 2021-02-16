# Drcalc
Drilling calculations
<div class="right">
<body>
  <table width="500" cellspacing="10" border="1">
    <col wigth="50">
    <col span="3" width="50" align="center">
    <col span="3" width="50" align="center">
    <tr>
      <td>&nbsp;</td><td>1</td><td>2</td><td>3</td>
    </tr>
    <tr>
      <td>длина, м</td></td><td>
        <input type="number" id="inp1">
        </td>
        <td>
          <span id="res1"> </span>
          <script>
            inp1.oninput=function(){
              res1.innerHTML=inp1.value*2;
            };
            </script>
          </td>
          <td>
           <span id="res2"> </span>
          <script>
            inp1.onchange=function(){
              res2.innerHTML=2*res1.innerHTML;
            };
            </script>
          </td>
    </tr>
    <tr>
      <td>2</td></td><td>1</td><td>2</td><td>3</td>
    </tr>
    <tr>
      <td>3</td></td><td>1</td><td>2</td><td>3</td>
    </tr>
</div>
