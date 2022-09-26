algoritimo cotação do Dólar

declaração 

  valor
  cotação 
  resultado
  

inicio 
  ESCREVA("Digite um valor, não pode converter menos que 10$");
     SE(VALOR>=10) ENTAO;
       LEIA(valor);
     SENAO(VALOR<10) ENTAO;
       ESCREVA("digite um valor apartir de 10$");
       
  ESCREVA("Digite Cotação atual");
  LEIA(cotação):
  resultado<-valor*cotação;

  ESCREVA("O valor em reais é:");
  ESCREVA(resultado);
