# primeiro
<!DOCTYPE html>
<html lang="en">
   <div id="ab"></div>
<head>
   <meta charset="UTF-8">
   <meta http-equiv="X-UA-Compatible" content="IE=edge">
   <meta name="viewport" content="width=device-width, initial-scale=1.0">
   <style type="text/css">

      div#ab {

          width: 200px;height: 200px;color: rgb(214, 226, 43);background: rgb(33, 33, 36);
     line-height: 200px;text-align: center;
      }
   </style>
   <title>Document</title>
</head>
<body>
   <h1>teste</h1>
  <div id ="ab"onclick="clicar()" onmouseenter="voltar()"onmouseout="sair()"> interaja</div> 
  <script>
   var ab= window.document.getElementById("ab")
 function clicar(){
 
  ab.innerText="entrou"
 }
 function voltar(){

ab.innerText="saiu"
 }
 function sair(){

   ab.innerText="sair"
 }

  </script>
</body>
</html>
