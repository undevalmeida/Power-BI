># CALCULATE
* Avalia uma expressão em um contexto de filtro modificado.
  ```
    % Percentual de faturamento online
    CALCULATE(<expression>[, <filter1> [, <filter2> [, …]]])
    
    Faturamento Total = SUM(Vendas[Faturamento])
    Faturamento Online = CALCULATE(SUM(Vendas[Faturamento]),Vendas[Loja]="Online")

    % Percentual Vendas Online = DIVIDE([Faturamento online],[Faturamento Total],"Sem Faturamento")
  ```
  * [Link da vídeo aula](https://www.youtube.com/watch?v=oZK-FJVL-kw)