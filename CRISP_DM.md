O Processo Padrão do Mercado para Mineração de Dados - CRISP-DM (Cross-Industry Standard Process for Data Mining) é um padrão de processo de mineração de dados que busca organizar o fluxo de trabalho necessário para um projeto de Ciência de Dados. Ele é composto por vários passos que podem ser seguidos para uma melhoria contínua. As etapas são:

##  Entendimento do negócio
Buscamos compreender quais são as necessidades, problemas e desafios do projeto. Esta etapa é realizada inicialmente e posteriormente para alinhamento das expectativas.

As necessidades identificadas para o projeto foram:
- Analisar se houve uma queda na receita dos filmes que, por consequência, indicaria queda na receita dos cinemas
- Analisar se houve uma diminuição dos filmes lançados
- Verificar se haveria uma relação entre o aumento do número de casos de Covid19 e a diminuição da receita dos filmes

## Entendimento dos dados
Nessa fase entendemos quais são os desafios sobre os dados. É um dado estruturado, texto, imagem ou som? Faltam dados? É desbalanceado? É big-data?

Ao analisar os dados, podemos observar que:
- Os dados tinham colunas desnecessárias para nossa análise
- O dataset era todo em texto, com números não padronizados entre os datasets
- Faltavam alguns dados, valores em branco ou desconhecidos
- Seria necessário avaliar se usaria os dados do mundo todo, ou de apenas algum local específico

## Preparação dos dados
Levantamento de quais as melhores técnicas para processamento desse tipo dado. Como lidar com o desbalanceamento, descartar ou preencher dados faltantes? Esta etapa exige muito tempo e poderá ser repetida diversas vezes.

Para preparar os dados, foi feito:
-Limpeza das colunas desnecessárias

## Modelagem
Basicamente, nenhum algoritmo tem um bom desempenho em todos os dados, como visto em no-free-lunch-theorem-for-machine-learning. Teremos de testar diferentes tipos de modelos em busca de qual possui o melhor desempenho. Esta etapa envolverá a busca por melhores parâmetros.

## Avaliação
É a apresentação das descobertas e dos resultados obtidos do modelo de melhor desempenho. O cliente poderá aceitar ou rejeitar o que foi apresentado, exigindo que um novo ciclo recomece a partir de um melhor entendimento do negócio.

## Implementação
Caso o cliente aceite os resultados obtidos e não necessite de ajustes, o próximo passo é a implementação da solução para que se passe a ser usada pelo cliente.
