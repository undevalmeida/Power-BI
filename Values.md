># VALUES
* Quando o parâmetro de entrada é um nome de coluna, uma tabela de única coluna.
* Quando o parâmetro de entrada é um nome de tabela, uma tabela das mesmas colunas é retornada.
  ```
  VALUES(<TableNameOrColumnName>)

  Ex: Total Taxa sem 2005=IF(COUNTROWS(VALUES(dCalendario[Ano]))=1;IF(VALUES(dCalendario[Ano])=2005;BLANK();[Total Taxas]);BLANK())

  ```
* [Link Vídeo Aula](https://www.youtube.com/watch?v=U_iOk3lhgfQ&list=PLWfPHxJoa7zvhuFU0saAaZsCVkrjDRGaN&index=3)