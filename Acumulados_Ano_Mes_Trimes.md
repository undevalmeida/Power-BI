># Acumulados Ano, Mês e Trimestre

```
= CALCULATE(<Expressão>;<Filtros>)

= DatesYTD(dCalendario[Data_Base])
= DatesQTD(dCalendario[Data)Base])
= DatesMTD(dCalendario[Data_Base])


Receita Acumulada (ano) = CALCULATE([Receita Total];DATESYTD(dCalendario[Data_Base]))

Receita Acumulada (Trimestre) = CALCULATE([Receita Total];DATESQTD(dCalendario[Data_Base]))

Receita Acumulada (Mês) = CALCULATE([Receita Total];DATESMTD(dCalendario[Data_Base]))
```
* [Link da Vídeo Aula](https://docs.microsoft.com/pt-br/dax/datesytd-function-dax)