># FILTER
* Retorna uma tabela que representa um subconjunto de outra tabela ou expressão.
  ```
    FILTER(<table>,<filter>)
    
    Ex: Quantidade Tecnologia = CALCULATE(COUNTROWS(FILTER(Vendas,AND(Vendas[Categoria] = "Tecnologia", Vendas[Preço de Venda] > 2000))))
  ```
  * [Link da vídeo aula](https://www.youtube.com/watch?v=S9BnjAti0KY)