# Practicing-function-php
<!DOCTYPE html>
<html>
<body>

<?php

                                  // </definição das funções>
function Botao() {
          if (botao == TRUE ) {
             echo "<br>Você tem 10 segundos para responder a pergunta exibida na tela.<br>";
               echo "Contagem regressiva iniciada:<br>";
                 $i = '10';
                    While ($i > 0 ) {     
                        /* Nesse caso vamos usar "echo" para ver o output, ent vamos
                            interpretar isso como a contagem regressiva */
                                echo $i . "<br>";
                                   $i--;
                                     if ($i == 0) {
                                        echo "Your time's over<br><br><br>";
                                          }
                                            }
                                              }
                                                else {
                                                   }
                                                     }
                                                           
                                                
 function Escolha () {
     echo "Escolha uma porta abaixo: <br><br>";
         echo "Porta 1<br>";
            echo "Porta 2";
               echo "<br><br>A porta escolhida foi: ";
                  }                                                                          
                                                
 function Proximo () {
    echo "Próximo desafio!<br><br>";
      }
                               
                               // </definição das funções>

Escolha();
echo "Porta 2<br><br>";
Botao();

Proximo ();

$Porta1 = TRUE;
$Porta2 = FALSE;


if ($Porta2 == TRUE) {
     Escolha();
     echo "Porta 2";
     Botao();
    }else{
    }
    
if ($Porta1 == TRUE) {
    Escolha();
    Echo "Porta 1<br>";
    echo "Parabéns, este é um atalho e você venceu o jogo sem passar pelo último desafio.";
    }
    else {
    }

?>

</body>
</html>
