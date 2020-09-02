# ATENÇÃO!!
ESSA ANÁLISE NÃO FOI CRIADO NO INTUITO POLÍTICO
SEM MIMIMI E ANTES DE FALAR ANALÍSE OS DADOS
---
# Lei de Benford Aplicado aos dados do siconv 

## Lei de Benford

A lei de Benford, também chamada de lei do primeiro dígito, lei de Newcomb-Benford e lei números anômalos refere-se à distribuição de dígitos em várias fontes de casos reais. Ao contrário da homogeneidade esperada, a lei afirma que em muitas coleções de números que ocorrem naturalmente, o primeiro dígito significativo provavelmente será pequeno. Sem homogeneidade, esta distribuição mostra que o dígito 1 tem 30% de chance de aparecer em um conjunto de dados estatísticos enquanto valores maiores tem menos possibilidade de aparecer.
Fonte: [Wikipedia](https://pt.wikipedia.org/wiki/Lei_de_Benford)

## Siconv

O SICONV é o sistema utilizado para captação de recursos para os Municípios e Entidades do Brasil, com esta ferramenta a entidade ou município poderá cadastrar propostas com a possibilidade de gerar um convênio e captar recursos para saúde, educação, infraestrutura e muitos outros programas que o governo disponibiliza para a população.
Fonte: [consultoriasquadra] (https://www.consultoriasquadra.com.br/blog/siconv/quer-saber-e-aprender-sobre-o-siconv-o-que-e-um-convenio/)

## Libs (Benford)
O projeto possui duas libs diferentes porém ambas aplica lei de benford. Essa estrategia foi utilizada para validar os resultados gerados. 
* [Benfordlaw](https://github.com/erdogant/benfordslaw)
* [Benford_py](https://github.com/milcent/benford_py)

