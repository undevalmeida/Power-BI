># SWITCH
* Avalia uma expressão em relação a uma lista de valores e retorna uma das várias expressões de resultado possíveis.
  ```
   = SWITCH(<expression>, <value>, <result>[, <value>, <result>]…[, <else>])
   
   Ex: =SWITCH(fDados[Filial];"FILIAL A";"REGIONAL 1";"FILIAL B"; "REGIONAL 1"; "FILIAL C"; "REGIONAL 3";...)
   
   
   Ex 2: =SWITCH(TRUE();[VALOR_VENDAS]<500;"NÃO HÁ PRÊMIOS";[VALOR_VENDA]<1000;"UM INGRESSO PARA SHOW";[VALOR_VENDAS]<3000;"CELULAR";"TV DE 50 POLEGADAS")
   Para o exmeplo 2. O momento em que atribuimos o 'TRUE()' você pode utilizar o 'SWITCH' como verificação de verdadeiro ou falso, assim, 
   sendo possível verificar se o vendedor tem direito ou não a prêmios.
  ```
* [Link da Vídeo Aula](https://www.youtube.com/watch?v=ERD0eMk71EY&list=PLWfPHxJoa7zvhuFU0saAaZsCVkrjDRGaN&index=5)
