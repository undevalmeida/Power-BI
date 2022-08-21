># CROSSFILTER
* A função não retorna nenhum valor; a função define apenas a direção de filtragem cruzada para a relação indicada, durante o tempo da consulta.
* Especifica a direção de filtragem cruzada a ser usada em um cálculo para uma relação existente entre duas colunas.
    * Ajuda a gerenciar as relações entre as tabelas.
    ```
    =CROSSFILTER(<ColimnName1>, <ColumnName2>, <direction>)

    Ex: Receita Cross = CALCULATE([Receita],CROSSFILTER(dNomes[ID],dVendedor[ID],Both))

    ```
* Na 'CROSSFILTER' existem alguns tipos de direção.
  * Both - Os filtros em qualquer um dos lados;
  * None - Nenhuma filtragem cruzada ocorre nessa relação;
  * OneWay - Os filtros de um lado ou o lado de pesquisa de uma relação filtram o outro lado. Esta opção não pode ser usada com uma relação de um para um. Não use esta opção em uma relação de muitos para muitos porque não está claro qual lado é o lado de pesquisa; em vez disso, use OneWay_LeftFiltersRight ou OneWay_RightFiltersLeft.
  * OneWay_LeftFiltersRight – os filtros no lado de ```<columnName1>``` filtram o lado de ```<columnName2>```. Esta opção não pode ser usada com uma relação de um para um ou de muitos para um.
  * OneWay_LeftFiltersRight – os filtros no lado de ```<columnName1>``` filtram o lado de ```<columnName2>```. Esta opção não pode ser usada com uma relação de um para um ou de muitos para um.
* [Link da vídeo aula](https://www.youtube.com/watch?v=Gzpr1jpUEi4&list=PLWfPHxJoa7zvhuFU0saAaZsCVkrjDRGaN&index=12)