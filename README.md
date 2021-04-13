# Ensaio sobre Rotas de caminhabilidade

Ensaio metodológico sobre desenvolvimento de rotas de caminhabilidade na cidade de São Paulo

## Motivação

Caminhar à pé é o modo de transporte mais frequente na cidade de São Paulo. Portanto, pesquisar e estudar essas rotas é tarefa urgente para os desafios e demandas.

## Objetivo

O objetivo deste repositório é testar e ensair métodos que vão poder ser utilizados para o estudo das redes de rotas caminháveis da cidade de São Paulo.

## Metodologia

A partir do geoprocessamento de alguns dados cartográficos disponíveis, como quadras prediais, quadras viárias, lotes e polígonos de vias, estamos propondo a desenho de um método preliminar para criação de uma rede.
Inicialmente é realizado a operação boolena de subtração da quadra predial em relação à quadra viária de uma região previamente estabelecida.
Com geometria resultante então é possível processar um eixo medial com PostGis e então conectar lotes e as travessias utilizando Python, GeoPandas e Shapely

## Resultados 

Os resultados preliminares estão disponibilizados na pasta `resultados` e o método descrito em Jupyter Notebooks 

## Próximos passos

A intenção é aumentar a àrea de processamento para um distrito inteiro e a cidade inteira. Paralelamente a isso ainda se faz necessário a identificação das faixas de pedestre e elementos físicos de travessia como passarelas, passagens subterrÂneas e viadutos.

