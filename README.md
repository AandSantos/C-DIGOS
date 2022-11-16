# C-DIGOS

PRIMEIRO_CÓDIGO  SISTEMA DE NOTAS APROVADO_REPROVADO

Primeira nota <input id="nota1" type="number"> <br />
   Segunda  nota <input id="nota2" type="number"> <br />
   Terceira nota <input id="nota2" type="number"> <br />
   <button onclick="media()">Calcular Média</button>

   <script type="text/javascript">

    function media(){
     var nota1 = parseFloat(document.getElementById("nota1").value);
     var nota2 = parseFloat(document.getElementById("nota2").value);
     var nota2 = parseFloat(document.getElementById("nota2").value)

     var media = (nota1 + nota2 + nota)/3;

     if(media >= 7)
      if(media==10)

      alert("Parabéns você foi aprovado")

      elif(media <7)
      alert("Você foi reprovado")}
      
      
      SEGUNDO_CÓDIGO  ALUNO_ESCREVENDO_NOTAS_NO_SISTEMA

      Primeira nota <input id="nota1" type="number"> <br />
   Segunda  nota <input id="nota2" type="number"> <br />
   
   <button onclick="media()">Calcular Média</button>

   <script type="text/javascript">

    function media(){
     var nota1 = parseFloat(document.getElementById("nota1").value);
     var nota2 = parseFloat(document.getElementById("nota2").value);
     
     var media = (nota1 + nota2)/2;

     if(media <7)

      alert("você precisa tirar acima de 7 para ser aprovado ")

   
   
