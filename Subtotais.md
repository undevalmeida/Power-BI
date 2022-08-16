># SUBTOTAIS
1. ISFILTERED()
   * Retornará TRUE quando a tabela ou coluna especificada estiver sendo filtrada diretamente.
2. HASONEVALUE()
    * Retorna VERDADEIRO quando o contexto para coluna foi filtrada para apenas um valor distinto
3. HASONEFILTER()
    * Retorna VERDADEIRO quando o número de valores diretamente filtrados na coluna é um
```
ISFILTERED(<TableNameOrColumnName>)
HASONEVALUE(<columnName>)
HASONEFILTER(<columnName>)

Ex: ISFILTERED=IF(ISFILTERED(fDados[Produto]);[Ticket Médio]);BLANK()
Ex2: HASONEVALUE=IF(HASONEVALUE(fDados[Produto]);[Ticket Médio];BLANK())
Ex3: HASONEFILTER=IF(HASONEFILTER(fDados[Produto]);[Ticket Médio];BLANK())
```
* [Link da vídeo aula](https://www.youtube.com/watch?v=Ne1x_H3pLk0&list=PLWfPHxJoa7zvhuFU0saAaZsCVkrjDRGaN&index=7)