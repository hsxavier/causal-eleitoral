# Aplicação de inferência causal via grafos causais (DAGs)

Este repositório contém dois notebooks jupyter de Python que tratam da teoria de inferência causal 
desenvolvida por Judea Pearl com grafos causais (grafos acíclicos direcionados). Fazemos uma 
demonstração dos métodos e conceitos com dados simulados e realizamos uma aplicação a um problema
de ciência política: qual o efeito causal médio do valor obtido para financiamento 
de campanha eleitoral na quantidade de votos obtidos?

## Estrutura do projeto

    .
    ├── README.md               <- Este documento
    ├── requirements.txt        <- Principais pacotes de python necessários
    ├── dados                   <- Diretório com os dados utilizados
    |   ├── brutos              <- Dados brutos, originais
    |   ├── limpos              <- Dados limpos, corrigidos, padronizados
    |   └── processados         <- Dados derivados 
    ├── analises                <- Análises feitas (notebooks de python)
    └── dados.tar.gz            <- Pasta de dados acima comprimida
	
## Descrição dos notebooks

### `analises/02_intro-to-causal-graphs.ipynb`

Uma explocação do funcionamento de estruturas básicas dos grafos causais (e.g., colisores, mediadores e confundidores) 
a partir de dados sintéticos lineares. Também aplicamos o método do ajuste no caso de modelos lineares gaussianos.
[[LINK]](analises/02_intro-to-causal-graphs.ipynb)

**AVISO:** Este notebook foi elaborado quando estávamos iniciando os estudos sobre inferência causal, então alguns termos
e conceitos podem estar sendo utilizados de maneira inapropriada.

### `analises/20_analise-verba-votos.ipynb`

Aplicação da teoria a um problema concreto e real: a medição do efeito causal médio do valor obtido para financiamento 
de campanha eleitoral na quantidade de votos obtidos.
[[LINK]](analises/20_analise-verba-votos.ipynb)

## Origem dos dados

Os dados utilizados aqui foram originalmente obtidos da página de [dados abertos do TSE](https://dadosabertos.tse.jus.br/dataset/).

## Contato

Este projeto foi produzido por [Henrique S. Xavier](http://henriquexavier.net) (<https://github.com/hsxavier>).
