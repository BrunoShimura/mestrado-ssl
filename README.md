# Aplicação de técnicas de aprendizado ativo junto a Contrastive Self-Supervised Learning em classificação de imagens

Código apresentado ao [Programa de Pós-Graduação em Ciência da Computação do Centro de Ciências Exatas e de Tecnologia da Universidade Federal de São Carlos](https://www.ppgcc.ufscar.br/pt-br), como parte dos requisitos para a obtenção do título de Mestre em Ciência da Computação.

## Resumo

O aprendizado auto-supervisionado tem ganhado destaque nos últimos anos por reduzir custos associados à rotulação de grandes volumes de dados. Entre suas abordagens, o aprendizado por contraste tornou-se central em visão computacional, baseando-se em aproximar amostras âncoras de amostras positivas e distanciá-las de negativas. Contudo, a seleção aleatória dessas amostras pode comprometer o desempenho do modelo. Este trabalho propõe a integração do aprendizado ativo ao aprendizado auto-supervisionado contrastivo, com o objetivo de selecionar amostras mais representativas durante o treinamento. A combinação dos dois paradigmas permite um processo mais eficiente: inicialmente, o modelo é treinado em grandes conjuntos de dados não rotulados para aprender representações gerais; em seguida, o aprendizado ativo é aplicado para identificar e rotular apenas os exemplos mais informativos, otimizando o treinamento. Os resultados obtidos demonstram que a união dessas técnicas pode gerar modelos mais robustos e eficientes em tarefas de classificação de imagens.

**Palavras-chave:** Aprendizado auto-supervisionado. Aprendizado por contraste. Aprendizado ativo.

## Abstract

Self-supervised learning has gained significant attention in recent years due to its ability to reduce the costs associated with labeling large datasets. Among its approaches, contrastive learning has become a central technique in computer vision, aiming to bring anchor samples closer to positive samples while pushing them away from negative ones. However, the random selection of these samples may negatively impact model performance. This work proposes the integration of active learning into contrastive self-supervised learning, with the goal of selecting more representative samples during training. By combining both paradigms, the training process becomes more efficient: first, the model is trained on large unlabeled datasets to learn general representations; then, active learning is employed to identify and label only the most informative examples, optimizing the overall process. The experimental results demonstrate that this combination leads to more robust and efficient models for image classification tasks.

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