># AVERAGEX + TOPN
* A função AVERAGEX faz avaliação de cada linha da tabela e pega o conjunto de valores, realiza o cálculo de média aritmética.
* A função TOPN retorna as 'N' linhas superiores da tabela especificada. 
  * ASC: Classifica do valor mais baixo para o valor mais alto,
  * DESC: Classifica do valor mais alto para o mais baixo.,
    * Valores nulos são tratados como os menores valores possíveis.
    ```
     = AVERGEX(<Tabela>, <Expressão>)
     = TOPN(<N_Value>, <Table>, <OrderBy_Expression>, [<Order>[, <OrderBy_Expression>, [<Order>]]…]) 
     Média dos 3 maiores = AVERAGEX(TOPN(3,fDados,fDados[VALOR VENDA],DESC),fDados[VALOR VENDA]))

     Média dos 3 menores = AVERAGEX(TOPN(3,fDados,fDadps[VALOR VENDA],ASC),fDados[VALOR VENDA]))

     ```
* [Link da Vídeo Aula](https://www.youtube.com/watch?v=o130bOTwdfs&list=PLWfPHxJoa7zvhuFU0saAaZsCVkrjDRGaN&index=2)
