# Dados brutos das SES

Dados baixados em: https://brasil.io/dataset/covid19/caso_full/

Data: 29/04/2021

OBS: A configuração para o filtro utilizado está no arquivo filtro.png

Informações úteis:
Essa tabela possui os casos confirmados e óbitos obtidos dos boletins das Secretarias Estaduais de Saúde (SES). Os dados foram enriquecidos, de forma que a partir do momento em que um município confirma um caso, ele sempre aparecerá nessa tabela (mesmo que para uma determinada data a SES não tenha liberado o boletim - nesse caso é repetido o dado do dia anterior).
Além de acessar os dados por essa interface você pode também baixar o dataset completo ou acessá-lo via API.

Campos da tabela:
Semana epidemiológica (epidemiological_week)
Data (date)
Dias a partir do primeiro caso (order_for_place)
UF (state)
Município (city)
Cód. IBGE (city_ibge_code)
Tipo de local (place_type)
Confirmados acum. (last_available_confirmed)
Confirmados acum./100k hab. (last_available_confirmed_per_100k_inhabitants)
Confirmações no dia (new_confirmed)
Óbitos acum. (last_available_deaths)
Óbitos no dia (new_deaths)
Óbitos/confirmados (last_available_death_rate)
População estimada 2019 (estimated_population)
É a última atualização? (is_last)
Dado repetido? (is_repeated)


