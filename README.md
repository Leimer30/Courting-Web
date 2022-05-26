<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta http-equiv="X-UA-Compatible" content="IE=edge">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>RemsCode</title>
</head>
<style type="text/css">
  body{
      background-color: brown;
  }
</style>
<body>
  <h1 id="resultText"></h1>
  <script>
    
    let response = prompt("Pwede ba kitang ligawan?❤ Oo o Hindi ?");
    let outputText = "";
    
    if (response=="Oo"){
      outputText = "I will love you for the rest of my life!❤";
    }else if(response=="Hindi"){
      outputText = "Sorry ganto lang ako☹ Sana maging masaya ka sa taong mamahalin mo☹";
    }else{
      outputText = "Wag mong i'skip! Sagutin mo muna yung tanong ko☹ Refresh mo ulit. UWUUU";
    }
    
    document.getElementById("resultText").innerHTML = outputText;
  </script>
</body>
</html>
