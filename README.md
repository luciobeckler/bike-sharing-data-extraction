# bike-sharing-data-extraction
## Extrair informações do banco de um banco de dados contendo informações sobre o compartilhamento de bicicletas.

### DESCRITIVO DAS COLUNAS DO DATASET
  **- rec_id:** índice do registro de locação; <br>
  **- datetime:** data;
  **- season:** estação do ano (1: inverno, 2: primavera, 3: verão, 4: outono). Relativo ao
  hemisfério norte;
  **- year:** ano (0: 2011, 1:2012);
  **- month:** mês (1 a 12);
  **- hour:** hora do dia (0 a 23);
  **- is_holiday:** booleano indicando feriado;
  **- weekday:** dia da semana (0: domingo, 1: segunda-feira, …, 6: sábado);
  **- is_workingday:** booleano indicando dia útil;
  **- weather_condition:** (1: limpo, 2: nublado, 3: chuva leve, 4: chuva forte);
  **- temp:** Temperatura escalada entre 0 e 1. Valor original em graus Celsius: -8 a 39;
  **- atemp:** Sensação térmica escalada entre 0 e 1. Valor original em graus Celsius: -16
  a 50;
  **- humidity:** Humidade relativa (0 a 1);
  **- windspeed:** Velocidade do vento escalada entre 0 e 1 (máximo original: 67);
  **- casual:** número de locações para usuários casuais;
  **- registered:** número de locações para usuários registrados;
  **- total_count:** contador total de aluguéis (casual+registered)
