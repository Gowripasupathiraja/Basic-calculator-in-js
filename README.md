# Basic-calculator-in-js
<html>
  <head>
        <title>Basic Calculator</title>
        <script language="javascript">
                function addNumbers()
                {
                        var val1 = parseInt(document.getElementById("value1").value);
                        var val2 = parseInt(document.getElementById("value2").value);
                        var ansD = document.getElementById("answer");
                        ansD.value = val1 + val2;
                }
                function subNumbers(){
                	    var val1 = parseInt(document.getElementById("value1").value);
                        var val2 = parseInt(document.getElementById("value2").value);
                        var ansD = document.getElementById("answer");
                        ansD.value = val1 - val2;
                }
                 function MulNumbers(){
                	    var val1 = parseInt(document.getElementById("value1").value);
                        var val2 = parseInt(document.getElementById("value2").value);
                        var ansD = document.getElementById("answer");
                        ansD.value = val1 * val2;
                }
                 function DivNumbers(){
                	    var val1 = parseInt(document.getElementById("value1").value);
                        var val2 = parseInt(document.getElementById("value2").value);
                        var ansD = document.getElementById("answer");
                        ansD.value = val1 - val2;
                }
        </script>
  </head>
  <body>
        <input type="text" id="value1" name="value1" ><br><br>
        <input type="text" id="value2" name="value2" ><br><br>
        <input type="button" value="Add"  onclick="javascript:addNumbers()"/>
        <input type="button" value="Sub"  onclick="javascript:subNumbers()"/>
        <input type="button" value="Mul"  onclick="javascript:MulNumbers()"/>
        <input type="button" value="Div"  onclick="javascript:DivNumbers()"/><br><br>

        <input type="text" id="answer">

  </body>
</html>
