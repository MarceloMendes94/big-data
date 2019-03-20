# Big Data

## Membros
1. Marcelo Passamai Mendes
2. Tadeu da Penha Júnior

## descricao da base de dados
A base de dados selecionada retrata a ocorrência de acidenetes na cidade de nova iorque, alguns dos seus dados são localidade, motivos, data e hora, envolvidos e etc. 
[link para download da base de dados](https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions/h9gi-nx95?fbclid=IwAR2XYyTJ3G03QmmkpV5kyPQ2r9dAR8_fhWquPDzGMc0HL2vRZEX192oduEI)
## Fast Immersion Canvas
![FIC](https://github.com/MarceloMendes94/big-data/blob/master/modelos/Fast%20Immersion%20Canvas.jpg)

## Fast modelling Canvas 
![FMC](https://github.com/MarceloMendes94/big-data/blob/master/modelos/canvas%202%20Acidentes%20NYC.jpg)


## Fast ELT Acidentes NYC
<table>
  <tr>
    <td colspan="6" align="center" >Fonte</td>
    <td colspan="5" align="center" >Alvo</td>
  </tr>
  <tr>
    <td >Sistema fonte</td>
    <td >Tabela fonte</td>
    <td >Nome(s) da(s) coluna(s) fonte</td>
    <td >Descrição</td>
    <td >Tipo de dado</td>
    <td >Regras ETL</td>
    <td >Tabela alvo</td>
    <td >Nome da coluna</td>
    <td >Descrição</td>
    <td >Tipo de Dado</td>
    <td >Exemplo de resultado</td>    
  </tr>
  
</table>

<br><br><br><br><br>


## 5W2H


### WHEN QUANDO
 |DATE|TIME|
 |----|----|

### WHERE ONDE
 |borough|latitude|longitude|location|ON STREET NAME|CROSS STREET NAME|OFF STREET NAME|
 |-------|--------|---------|--------|--------------|-----------------|---------------|

### WHAT  O QUE
|NUMBER OF PERSONS INJURED|NUMBER OF PERSONS KILLED|NUMBER OF CYCLIST INJURED|NUMBER OF CYCLIST KILLED|NUMBER OF MOTORIST INJURED|NUMBER OF MOTORIST KILLED|
|-------------------------|------------------------|-------------------------|------------------------|--------------------------|-------------------------|

### WHY JUSTIFICATIVA
|CONTIBUTING FACTOR VEHICLE 1|CONTIBUTING FACTOR VEHICLE 2|CONTIBUTING FACTOR VEHICLE 3|CONTIBUTING FACTOR VEHICLE 4|CONTIBUTING FACTOR VEHICLE 5|
|----------------------------|----------------------------|----------------------------|----------------------------|----------------------------|

### WHO QUEM
|VEHICLE TYPE CODE 1|VEHICLE TYPE CODE 2|VEHICLE TYPE CODE 3|VEHICLE TYPE CODE 4|VEHICLE TYPE CODE 5|
|-------------------|-------------------|-------------------|-------------------|-------------------|

### HOW COMO SERÁ FEITO
|VEHICLE TYPE CODE N|CONTIBUTING FACTOR VEHICLE N|
|-------------------|----------------------------|

### HOW MUCH QUANTO CUSTARÁ

    ????

## Mapa de acidentes
[link para o mapa](https://nbviewer.jupyter.org/github/MarceloMendes94/big-data/blob/master/mapa_nyc.ipynb) 
