># MAXX
* Devolve o valor mais alto de um conjunto de expressões avaliado numa tabela.
    ```
    =MAXX(<Tabela>,<Expressão>)
    
    Ex: Maior Venda = MAXX(fDados, fDados[Preço Unitário]*fDados[Quantidade])
    
    Ex2: Maior Lucro = MAXX(fDados,(fDados[Preço Unitário]*[fDados[Quantidade])*(fDados[Margem Produto]-fDados[Desconto]))
    ```

># MINX
* Devolve o valor mais baixo de um conjunto de expressões avaliado numa tabela.
    ```
    =MINXX(<Tabela,<Expressão>)

    Ex: Menor Venda = MINX(fDados, fDados[Preço Unitário]*fDados[Quantidade])
    
    Ex2: Menor Lucro = MINX(fDados,(fDados[Preço Unitário]*[fDados[Quantidade])*(fDados[Margem Produto]-fDados[Desconto]))
    ```
* [Link da Vídeo Aula](https://www.youtube.com/watch?v=4F9aixN-EiM&list=PLWfPHxJoa7zvhuFU0saAaZsCVkrjDRGaN&index=1)