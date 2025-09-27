# Aplicação de técnicas de aprendizado ativo junto a Contrastive Self-Supervised Learning em classificação de imagens

Código apresentado ao [Programa de Pós-Graduação em Ciência da Computação do Centro de Ciências Exatas e de Tecnologia da Universidade Federal de São Carlos](https://www.ppgcc.ufscar.br/pt-br), como parte dos requisitos para a obtenção do título de Mestre em Ciência da Computação.

## Resumo

Self-supervised learning tem ganhado muita popularidade nos últimos anos, evitando custos computacionais na rotulação de uma grande quantidade de dados. Especificamente, aprendizado por contraste que tornou-se um componente dominante em visão computacional com um dos princípios de aproximar as imagens âncoras (imagem original) das imagens positivas e afastar as imagens âncoras das imagens negativas. Porém, a escolha aleatória dessas imagens pode influenciar diretamente nos resultados do modelo. Assim, o objetivo do trabalho é escolher amostras mais representativas para o treinamento do modelo, aplicando o paradigma de aprendizado ativo e comparar com modelos já existentes. Combinar aprendizado auto-supervisionado com aprendizado ativo pode resultar em um sistema altamente eficiente. O modelo pode inicialmente ser treinado em um grande conjunto de dados não rotulados, aprendendo representações gerais. Em seguida, ele pode usar aprendizado ativo para identificar os dados mais informativos que ainda precisam de rótulos, otimizando assim o processo de treinamento.

**Palavras-chave:** Self-supervised learning. Contrastive learning. Active learning.

## Versões das bibliotecas

- **python** : 3.9.21
- **numpy** : 1.24.3
- **torch** : 2.6.0
- **tensorflow** : 2.15.0
- **keras** : 2.15.0
- **matplotlib** : 3.7.2
- **sklearn** : 1.6.1
- **pandas** : 2.2.3
- **torchvision** : 0.21.0