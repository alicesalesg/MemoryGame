# MemoryGame
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Eventos DOM </title>
    <style>
        
       div#area1 {
            font: normal 20pt Times; /* fonte e tamanho do texto*/
            background-color: rgb(75, 49, 98);  /*cor do fundo*/
            color: white; /*cor do texto, no caso da div*/
            width: 200px;  /*largura do fundo roxo*/
            height: 200px; /*altura do fundo roxo*/
            line-height: 200px; /* posição do texto na vertical*/
            text-align: center; /* posição do texto na horizontal*/
            position: relative;
            margin-bottom: 20px; /*dá margem*/
        }

        div#area2 {
            font: normal 20pt Times; /* fonte e tamanho do texto*/
            background-color: rgb(113, 96, 128);  /*cor do fundo*/
            color: white; /*cor do texto, no caso da div*/
            width: 200px;  /*largura do fundo roxo*/
            height: 200px; /*altura do fundo roxo*/
            line-height: 200px; /* posição do texto na vertical*/
            text-align: center; /* posição do texto na horizontal*/
            margin-bottom: 20px; /*dá margem*/
            
        }
        div#area3 {
            font: normal 20pt Times; /* fonte e tamanho do texto*/
            background-color:  rgb(75, 49, 98);  /*cor do fundo*/
            color: white; /*cor do texto, no caso da div*/
            width: 200px;  /*largura do fundo roxo*/
            height: 200px; /*altura do fundo roxo*/
            line-height: 200px; /* posição do texto na vertical*/
            text-align: center; /* posição do texto na horizontal*/
            margin-bottom: 20px;
        }
        div#area4 {
            font: normal 20pt Times; /* fonte e tamanho do texto*/
            background-color: rgb(113, 96, 128);  /*cor do fundo*/
            color: white; /*cor do texto, no caso da div*/
            width: 200px;  /*largura do fundo roxo*/
            height: 200px; /*altura do fundo roxo*/
            line-height: 200px; /* posição do texto na vertical*/
            text-align: center; /* posição do texto na horizontal*/
            margin-bottom: 20px;
        }
        div#area5 {
            font: normal 20pt Times; /* fonte e tamanho do texto*/
            background-color:  rgb(75, 49, 98);  /*cor do fundo*/
            color: white; /*cor do texto, no caso da div*/
            width: 200px;  /*largura do fundo roxo*/
            height: 200px; /*altura do fundo roxo*/
            line-height: 200px; /* posição do texto na vertical*/
            text-align: center; /* posição do texto na horizontal*/
            margin-bottom: 20px;
        }
        div#area6 {
            font: normal 20pt Times; /* fonte e tamanho do texto*/
            background-color: rgb(113, 96, 128);  /*cor do fundo*/
            color: white; /*cor do texto, no caso da div*/
            width: 200px;  /*largura do fundo roxo*/
            height: 200px; /*altura do fundo roxo*/
            line-height: 200px; /* posição do texto na vertical*/
            text-align: center; /* posição do texto na horizontal*/
            margin-bottom: 20px;
        }
        div#area7 {
            font: normal 20pt Times; /* fonte e tamanho do texto*/
            background-color:  rgb(75, 49, 98);  /*cor do fundo*/
            color: white; /*cor do texto, no caso da div*/
            width: 200px;  /*largura do fundo roxo*/
            height: 200px; /*altura do fundo roxo*/
            line-height: 200px; /* posição do texto na vertical*/
            text-align: center; /* posição do texto na horizontal*/
            margin-bottom: 20px;
        }
        div#area8 {
            font: normal 20pt Times; /* fonte e tamanho do texto*/
            background-color: rgb(113, 96, 128);  /*cor do fundo*/
            color: white; /*cor do texto, no caso da div*/
            width: 200px;  /*largura do fundo roxo*/
            height: 200px; /*altura do fundo roxo*/
            line-height: 200px; /* posição do texto na vertical*/
            text-align: center; /* posição do texto na horizontal*/
            margin-bottom: 20px;
        }
    </style>
  
</head>
<body>
    <div id="area1" onclick="clicar1()" onmouseenter="entrar1()"onmouseout="sair1()">
        1
    </div>

    <div id = "area2" onclick="clicar2()" onmouseenter="entrar2()" onmouseout="sair2()">
        2
    </div>

    <div id = "area3" onclick="clicar3()" onmouseenter="entrar3()" onmouseout="sair3()">
        3
    </div>
    <div id = "area4" onclick="clicar4()" onmouseenter="entrar4()" onmouseout="sair4()">
        4
    </div>
    <div id = "area5" onclick="clicar5()" onmouseenter="entrar5()" onmouseout="sair5()">
        5
    </div>
    <div id = "area6" onclick="clicar6()" onmouseenter="entrar6()" onmouseout="sair6()">
        6
    </div>
    <div id = "area7" onclick="clicar7()" onmouseenter="entrar7()" onmouseout="sair7()">
        7
    </div>
    <div id = "area8" onclick="clicar8()" onmouseenter="entrar8()" onmouseout="sair8()">
        8
    </div>
   
    

    <script> 
         var area1 = window.document.getElementById('area1')
        function clicar1() {
            area1.innerText = 'LEÃO'
         }
        function entrar1(){
            area1.style.background = "black"
        }
        function sair1(){
            area1.style.background = "rgb(75, 49, 98)"
            area1.innerText = '1'
        }
        
         var area2 = window.document.getElementById('area2')
        function clicar2() {
            area2.innerText = 'GIRAFA'
        }
        function entrar2(){
            area2.style.background = 'black'
        
        }
        function sair2(){
            area2.style.background =' rgb(113, 96, 128)'
            area2.innerText = '2'
        }
       
         var area3 = window.document.getElementById('area3')
        function clicar3() {
            area3.innerText = 'TUBARÃO'
        }
        function entrar3(){
            area3.style.background = 'black'
        
        }
        function sair3(){
            area3.style.background = 'rgb(75, 49, 98)'
            area3.innerText = '3'
        }
        
        var area4 = window.document.getElementById('area4')
        function clicar4() {
            area4.innerText = 'ELEFANTE'
        }
        function entrar4(){
            area4.style.background = 'black'
        
        }
        function sair4(){
            area4.style.background =' rgb(113, 96, 128)'
            area4.innerText = '4'
        }
        
        var area5 = window.document.getElementById('area5')
        function clicar5() {
            area5.innerText = 'TUBARÃO'
        }
        function entrar5(){
            area5.style.background = 'black'
        
        }
        function sair5(){
            area5.style.background ='rgb(75, 49, 98)'
            area5.innerText = '5'
        }
        
        var area6 = window.document.getElementById('area6')
        function clicar6() {
            area6.innerText = 'LEÃO'
        }
        function entrar6(){
            area6.style.background = 'black'
        
        }
        function sair6(){
            area6.style.background =' rgb(113, 96, 128)'
            area6.innerText = '6'
        }
        
        var area7 = window.document.getElementById('area7')
        function clicar7() {
            area7.innerText = 'ELEFANTE'
        }
        function entrar7(){
            area7.style.background = 'black'
        
        }
        function sair7(){
            area7.style.background ='rgb(75, 49, 98)'
            area7.innerText = '7'
        }
        
        var area8 = window.document.getElementById('area8')
        function clicar8() {
            area8.innerText = 'GIRAFA'
        }
        function entrar8(){
            area8.style.background = 'black'
        
        }
        function sair8(){
            area8.style.background =' rgb(113, 96, 128)'
            area8.innerText = '8'
        }
         </script>
   

    
</body>
</html>
