># INTERSECT
* Retorna a interseção de linha entre duas tabelas, retendo as duplicatas.
  ```
  =INTERSECT(<Tabela 1>,<Tabela 2>)
  Ex: REALIZOU VENDAS= 
                    COUNTAX()  
                        INTERSECT(
                            VALUES(fDados[ID_VENDEDOR]),
                            DISTINCT(fDados[ID_VENDEDOR])
                            ),[N. VENDAS]
                        )
  ```
  * [Link da vídeo aula](https://www.youtube.com/watch?v=TdP26Eoyd0Q&list=PLWfPHxJoa7zvhuFU0saAaZsCVkrjDRGaN&index=9)