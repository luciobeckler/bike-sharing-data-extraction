# bike-sharing-data-extraction
## Extrair informações do banco de um banco de dados contendo informações sobre o compartilhamento de bicicletas.

### DESCRITIVO DAS COLUNAS DO DATASET
  **- rec_id:** índice do registro de locação; <br>
  **- datetime:** data; <br>
  **- season:** estação do ano (1: inverno, 2: primavera, 3: verão, 4: outono). Relativo ao
  hemisfério norte; <br>
  **- year:** ano (0: 2011, 1:2012); <br>
  **- month:** mês (1 a 12); <br>
  **- hour:** hora do dia (0 a 23); <br>
  **- is_holiday:** booleano indicando feriado; <br>
  **- weekday:** dia da semana (0: domingo, 1: segunda-feira, …, 6: sábado); <br>
  **- is_workingday:** booleano indicando dia útil; <br>
  **- weather_condition:** (1: limpo, 2: nublado, 3: chuva leve, 4: chuva forte); <br>
  **- temp:** Temperatura escalada entre 0 e 1. Valor original em graus Celsius: -8 a 39; <br>
  **- atemp:** Sensação térmica escalada entre 0 e 1. Valor original em graus Celsius: -16
  a 50; <br>
  **- humidity:** Humidade relativa (0 a 1); <br>
  **- windspeed:** Velocidade do vento escalada entre 0 e 1 (máximo original: 67); <br>
  **- casual:** número de locações para usuários casuais; <br>
  **- registered:** número de locações para usuários registrados; <br>
  **- total_count:** contador total de aluguéis (casual+registered)<br>
