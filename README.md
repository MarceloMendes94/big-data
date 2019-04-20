# Big Data

## Membros
1. Marcelo Passamai Mendes
2. Tadeu da Penha Júnior

## Descricao da base de dados
A base de dados selecionada retrata a ocorrência de acidenetes na cidade de nova iorque, alguns dos seus dados são localidade, motivos, data e hora, envolvidos e etc. <br>
[link para download da base de dados](https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions/h9gi-nx95?fbclid=IwAR2XYyTJ3G03QmmkpV5kyPQ2r9dAR8_fhWquPDzGMc0HL2vRZEX192oduEI)
<br>
# Modelagem do DW
## Fast Immersion Canvas
![FIC]()

## Fast modelling Canvas 
![FMC]()

## Fast ELT Acidentes NYC
[pdf]()
<br><br>
## PDI gerando dimensões

### carga dos dados

![carga](imagens/carga.png)

<br><br>

### dimensão local
![dim_local](imagens/dim_local.png)

<br><br>

### dimensão hora
![dim_hora](imagens/dim_hora.png)

<br><br>

### dimensão evento
![dim_evento](imagens/dim_evento_certo.png)

<br><br>

### criação da tabela fato
![tabela fato](imagens/tabelafato.png)

<br><br>

## Mapa de acidentes
[link para o mapa](https://nbviewer.jupyter.org/github/MarceloMendes94/big-data/blob/master/mapa_nyc.ipynb) 
