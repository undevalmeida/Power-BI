># USERELATIONSHIP
* A função não retornará nenhum valor, mas apenas habilitará a relação indicada durante o cálculo.
  ```
    =USERELATIONSHIP(<columnName1>,<columnName2>)

    Ex: N. Entregas REalizadas = CALCULATE(COUNTROWS(fDados);USERRELATIONSHIP(dCalendario[Data_Base];fDados[Data_Entrega]))
  ```
  * [Link da vídeo aula](https://www.youtube.com/watch?v=AJIIdXKIk0I&list=PLWfPHxJoa7zvhuFU0saAaZsCVkrjDRGaN&index=8)