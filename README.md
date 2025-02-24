Análise de Dados Imobiliários

Descrição do Projeto

Este projeto tem como objetivo analisar o arquivo trabalho1.csv, que contém informações sobre imóveis, incluindo:

Área (m²)

Número de quartos

Número de vagas de garagem

Valor unitário (R$ por m²)

A análise foi realizada utilizando a linguagem Python, com o uso de bibliotecas de manipulação de dados e modelagem estatística.

Ferramentas Utilizadas

Pandas para manipulação dos dados.

NumPy para cálculos estatísticos.

Scikit-learn para modelagem de regressão linear.

Matplotlib para visualização dos dados.

SciPy para cálculos estatísticos adicionais.

Análises Realizadas

Leitura e Exibição dos Dados

Importação do dataset e verificação inicial dos dados.

Análise Estatística

Cálculo da média, mediana, desvio-padrão e média aparada dos valores unitários.

Visualização dos Dados

Gráfico de dispersão: Relação entre área e valor unitário.

Boxplot para distribuição dos valores unitários.

Regressão Linear Simples

Predição do valor unitário com base apenas na área do imóvel.

Cálculo do coeficiente angular e intercepto da reta de regressão.

Coeficiente de determinação (R²) e coeficiente de correlação.

Regressão Linear Múltipla

Predição do valor unitário considerando múltiplas variáveis:

Área e número de quartos

Área e número de vagas de garagem

Avaliação dos coeficientes da regressão.

Estimação de Preços de Imóveis

Cálculo do preço estimado para um imóvel de 100m², com 3 quartos e 2 vagas usando:

Média dos valores unitários.

Regressão linear simples.

Regressão linear múltipla.

Comparação das estimativas e análise das diferenças.

Resultados Principais

Média dos valores unitários: R$8.374,22

Regressão Linear Simples (baseada apenas na área): R$8.348,43

Regressão Linear Múltipla (considerando quartos e vagas): R$8.226,85

Diferença entre as estimativas: valores relativamente próximos, mas indicando baixa correlação entre as variáveis.

O coeficiente de correlação entre área e valor unitário foi -0,07, sugerindo fraca relação linear.

Conclusão

A análise mostrou que a área do imóvel, por si só, não é um forte preditor do valor unitário, sendo necessário considerar outras variáveis para estimar preços de maneira mais confiável. Apesar das diferenças entre as abordagens, os valores estimados foram relativamente próximos.

Como Executar o Projeto
