# Detecção de Trocadilhos em Português

Projeto acadêmico de Inteligência Artificial desenvolvido como parte da avaliação **N3**, com foco na aplicação de técnicas de Aprendizado de Máquina (*Machine Learning*) e Processamento de Linguagem Natural (PLN) para identificação e classificação de trocadilhos em textos escritos em português.

## Sobre o Projeto

O objetivo deste projeto é desenvolver um modelo de Inteligência Artificial capaz de identificar se determinado texto contém um trocadilho.

A proposta é baseada na competição **[Competição de Puns](https://www.kaggle.com/competitions/competicao-de-puns)**, disponibilizada na plataforma Kaggle, que propõe o desenvolvimento de algoritmos de aprendizado de máquina para a detecção de humor na língua portuguesa, especificamente por meio da identificação de trocadilhos.

## Objetivos

- Desenvolver um modelo de classificação de textos utilizando técnicas de Inteligência Artificial.
- Explorar métodos de Processamento de Linguagem Natural aplicados à língua portuguesa.
- Analisar e preparar dados textuais para treinamento de modelos.
- Identificar padrões linguísticos associados à construção de trocadilhos.
- Treinar e avaliar algoritmos de Aprendizado de Máquina.
- Analisar o desempenho dos modelos na tarefa de classificação.

## Base de Dados

O projeto utiliza o **Puntuguese**, um corpus de textos contendo trocadilhos em português brasileiro e europeu.

Os dados foram coletados e selecionados manualmente a partir de três fontes:

- Blog *Maiores e Melhores*;
- Página do Instagram *O Sagrado Caderno das Piadas Secas*;
- *UTC – Ultimate Trocadilho Challenge*, dos Castro Brothers, no YouTube.

### Características do dataset

| Característica | Informação |
|---|---|
| Nome | Puntuguese |
| Conteúdo | Trocadilhos em português |
| Idiomas | Português brasileiro e europeu |
| Quantidade de arquivos | 3 |
| Formatos | JSONL e CSV |
| Tamanho | Aproximadamente 1,25 MB |
| Licença informada | MIT |

### Estrutura dos dados

Os registros apresentam informações utilizadas no processamento e na classificação dos textos, incluindo:

- `id`: identificador do registro;
- `text`: conteúdo textual;
- `label`: classificação associada ao texto;
- `tokens`: palavras e elementos resultantes da tokenização;
- `labels`: informações de rotulação em nível de token.

## Etapas de Desenvolvimento

O desenvolvimento da solução contempla as seguintes etapas:

1. **Análise exploratória:** compreensão da estrutura, características e distribuição dos dados.
2. **Pré-processamento textual:** preparação e tratamento dos textos.
3. **Tokenização:** divisão dos textos em unidades linguísticas.
4. **Representação textual:** transformação dos dados em representações adequadas para os algoritmos.
5. **Treinamento:** aplicação de algoritmos de aprendizado de máquina.
6. **Avaliação:** análise do desempenho dos modelos por meio de métricas de classificação.
7. **Predição:** identificação de possíveis trocadilhos em novos textos.

## Conceitos Aplicados

- Inteligência Artificial;
- Machine Learning;
- Processamento de Linguagem Natural (PLN);
- Classificação de textos;
- Tokenização;
- Análise de dados;
- Aprendizado supervisionado.

## Resultados

Os resultados dos experimentos serão apresentados conforme o desenvolvimento do projeto, incluindo os modelos utilizados, métricas de avaliação e análises de desempenho.

## Contexto Acadêmico

Este projeto foi desenvolvido como parte da avaliação N3, com o propósito de aplicar conhecimentos de Inteligência Artificial na resolução de um problema relacionado à compreensão e classificação de linguagem natural.

## Referências

- **Competição:** [Competição de Puns – Kaggle](https://www.kaggle.com/competitions/competicao-de-puns)
- **Dataset:** Puntuguese.
- **Área de aplicação:** Inteligência Artificial e Processamento de Linguagem Natural.

---

Desenvolvido para fins acadêmicos.