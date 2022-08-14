># ALLEXCEPT
* Remove todos os filtros de contexto na tabela, exceto filtros aplicados às colunas especificadas.
  ```
    = ALLEXCEPT(<table>,<column>[,<column>[,…])

    Ex: Total Geral Ano=CALCULATE([TOTAL VENDAS];ALLEXCEPT(fDados;fDados[Ano]))
    
    O 'Alexcept' está removendo todos os filtros do contexto exceto da coluna '[Ano]'
  ```
[Link da vídeo aula](https://www.youtube.com/watch?v=je-IeDOgaYY&list=PLWfPHxJoa7zvhuFU0saAaZsCVkrjDRGaN&index=6)