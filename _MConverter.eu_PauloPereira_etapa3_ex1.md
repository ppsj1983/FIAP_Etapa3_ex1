Importação do arquivo

![](media/image1.png){width="4.779241032370954in"
height="3.0564905949256342in"}

seleção do método inserir para criação de uma nova tabela e importação
de dados

![](media/image4.png){width="4.841741032370954in"
height="3.056247812773403in"}

seleção de todas as colunas

![](media/image2.png){width="4.820907699037621in"
height="3.131187664041995in"}

identificação de duas colunas com nomes contendo caracteres especial,
gerando uma critica com necessidade de correção

![](media/image5.png){width="4.675074365704287in"
height="2.8889162292213473in"}

correções efetuadas retirada dos caracteres especiais

![](media/image9.png){width="4.643824365704287in"
height="2.969887357830271in"}

finalização da etapa de importação

![](media/image10.png){width="4.022342519685039in"
height="2.492248468941382in"}

criação da nova tabela DADOS SENSORES

![](media/image12.png){width="4.487574365704287in"
height="2.4226935695538057in"}

1ª Consulta

- Exibição de todos os dados da tabela

![](media/image11.png){width="4.414657699037621in"
height="2.5153280839895014in"}

2ª consulta plantação de trigo

select com utilização de um critério para filtro, utilizando operador
logico '='

CROP_TYPE = \'Wheat\'

![](media/image8.png){width="4.442510936132983in"
height="2.917288932633421in"}

3ª consulta plantação de trigo com tipo de irrigação gotejamento

select com utilização de dois critério para filtro, utilizando operador
logico '='

CROP_TYPE = \'Wheat\' and IRRIGATION_TYPE = \'Drip\'

![](media/image3.png){width="6.267716535433071in"
height="3.4583333333333335in"}

4ª consulta plantação diferente de trigo com nivel de pH superior a 700

utilização os operadores logicos diferente '\<\>' e maior '\>'

CROP_TYPE \<\> \'Wheat\' AND SOIL_PH \> 700

![](media/image7.png){width="5.560491032370954in"
height="3.740038276465442in"}

5 consulta colheitas diferentes de trigo com pH maior que 700 e previsão
de colheita entre 01/ma/24 e 30/jul/24

CROP_TYPE \<\> \'Wheat\'

AND SOIL_PH \> 700

AND HARVEST_DATE BETWEEN TO_DATE(\'01/05/2024\', \'DD/MM/YYYY\') AND
TO_DATE(\'30/07/2024\', \'DD/MM/YYYY\')

![](media/image6.png){width="5.633407699037621in"
height="3.259524278215223in"}
