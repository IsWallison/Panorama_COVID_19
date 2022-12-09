# Panorama_COVID_19
[![author](https://img.shields.io/badge/author-Wallison-red.svg)](https://www.linkedin.com/in/wallison-borges-48312516a/) [![](https://img.shields.io/badge/python-3.7+-blue.svg)](https://www.python.org/downloads/release/python-365/) [![GPLv3 license](https://img.shields.io/badge/License-GPLv3-blue.svg)](http://perso.crans.org/besson/LICENSE.html) [![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/IsWallison/Project_airbnb/issues)

<p align="center">
  <img src="virus-cells-floating-particles.jpg" >
</p>

# Analise dos Dados do COVID_19
A Covid-19 é uma infecção respiratória aguda causada pelo coronavírus SARS-CoV-2, potencialmente grave, de elevada transmissibilidade e de distribuição global.

O SARS-CoV-2 é um betacoronavírus descoberto em amostras de lavado broncoalveolar obtidas de pacientes com pneumonia de causa desconhecida na cidade de Wuhan, província de Hubei, China, em dezembro de 2019. Pertence ao subgênero Sarbecovírus da família Coronaviridae e é o sétimo coronavírus conhecido a infectar seres humanos.

Os coronavírus são uma grande família de vírus comuns em muitas espécies diferentes de animais, incluindo o homem, camelos, gado, gatos e morcegos. Raramente os coronavírus de animais podem infectar pessoas e depois se espalhar entre seres humanos como já ocorreu com o MERS-CoV e o SARS-CoV-2. Até o momento, não foi definido o reservatório silvestre do SARS-CoV-2.

# Dataset
O conjunto de dados pode ser facilmente encontrado aqui: https://github.com/owid/covid-19-data/blob/master/public/data/owid-covid-data.csv?raw=true

# Bibliotecas necessárias

* Pandas
* Matplotlib
* Seaborn 
* Datetime
Você também precisará de um software que possa executar um notebook python .ipynb




# Resultados

Neste notebook pudemos estudar um pouco os dados referentes ao COVID-19. Tendo o banco de dados sido obtido pela organização Our World in Data, no mês de dezembro de 2022, com isso resultados obtidos refletem somente o momento em que os dados foram analisados.


##Em relação às mortes, os países que lideravam aos 07 de Dezembro de 2022 em relação ao número de mortes eram: 

* Estados Unidos - 1.082.224 de mortes;
* Brasil - 690.229 de mortes;
* Índia - 530.638.0 de mortes;

Estados Unidos, Brasil e Índia representam mais de 34% de todas as mortes do mundo.


## Em relação aos casos, os países que lideravam aos 07 de Dezembro de 2022 eram:

* Estados Unidos - 99.077.996
* Índia - 44.675.172 
* França - 38.223.893



## Em relação aos países com a maior porcentagem de mortes em relação a sua população total.

* Peru - 0.64
* Bulgaria - 0.56
* Bosnia and Herzegovina - 0.50

## Aparentemente que países  com os maiores PIB per capital tendem a ter menos mortes de COVID-19.

  País  | PIB per capital | Mortes | Population
  ------------|-----------|-----------|-----------
  Qatar | 116.935,60 | 685 | 2.695.131
  Macao | 104.861,85 | 6 | 695.180
  Luxemburgo | 94.277,96 | 1168 | 647.601
  Singapura| 85.535,38 | 1707 | 5.637.022
  Brunei | 71.809,25 | 225 | 449.002

#COVID-19 no Brasil:

* O primeiro caso no Brasil ocorreu em 26 de fevereiro de 2020 e a primeira morte no Brasil ocorreu em 17 de abril de 2020, foram 20 dias do primeiro caso até a primeira morte.

* Relação entre pessoas vacinadas e novas mortes, quanto mais pessoas vacinada menos mortes ocorrem.
