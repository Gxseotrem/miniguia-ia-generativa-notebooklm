# 🤖 Miniguia de Inteligência Artificial Generativa com NotebookLM

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![Tema](https://img.shields.io/badge/tema-IA%20Generativa-blue)
![Ferramenta](https://img.shields.io/badge/ferramenta-NotebookLM-orange)

> Projeto desenvolvido como parte do desafio da DIO sobre aprendizagem ativa com Inteligência Artificial e uso do NotebookLM.

## 📚 Sobre o projeto

Este projeto apresenta um **Caderno Temático sobre Inteligência Artificial Generativa**, desenvolvido com apoio do **NotebookLM** como ferramenta de aprendizagem ativa.

A proposta foi utilizar a Inteligência Artificial não apenas para obter respostas prontas, mas como ferramenta para pesquisar, organizar informações, comparar fontes, formular perguntas, testar prompts, identificar limitações e consolidar conhecimentos.

## 🎯 Contexto e objetivos

### Contexto

A Inteligência Artificial Generativa passou a fazer parte de atividades acadêmicas e profissionais, sendo utilizada em geração de textos, imagens, código, análise de documentos, educação e automação.

Como estudante de Ciência da Computação, escolhi o tema para compreender os conceitos por trás das ferramentas de IA e desenvolver uma metodologia de estudo baseada em fontes e pensamento crítico.

### Objetivo geral

Construir uma base de conhecimento introdutória sobre **Inteligência Artificial Generativa**, utilizando o NotebookLM para realizar aprendizagem baseada em fontes selecionadas.

### Objetivos específicos

- Compreender IA Generativa e LLMs.
- Estudar tokens, contexto, Transformers e atenção.
- Compreender Engenharia de Prompts.
- Estudar RAG.
- Identificar alucinações e vieses.
- Conhecer princípios de uso responsável da IA.
- Desenvolver prompts reutilizáveis.
- Documentar testes, erros e refinamentos.

## 🧰 Ferramentas

| Ferramenta | Utilização |
|---|---|
| NotebookLM | Organização das fontes, perguntas e estudo |
| GitHub | Versionamento e publicação |
| Markdown | Documentação |
| Fontes abertas | Base de conhecimento |

## 🔎 1. Curadoria das fontes

Foram selecionadas cinco fontes abertas, combinando material introdutório, documentação técnica, referência institucional e publicação acadêmica.

| Fonte | Utilização |
|---|---|
| IBM — IA Generativa | Fundamentos e aplicações |
| Google for Developers — LLMs | LLMs, tokens, contexto e Transformers |
| Google Cloud — Prompt Design | Engenharia de prompts |
| NIST — GenAI Profile | Riscos e uso responsável |
| Lewis et al. — RAG | Retrieval-Augmented Generation |

Os links e a justificativa de seleção estão em [`fontes/fontes.md`](fontes/fontes.md).

## 🧠 2. Miniguia de estudo

### 2.1 Inteligência Artificial Generativa

IA Generativa é uma área da Inteligência Artificial capaz de produzir novos conteúdos a partir de padrões aprendidos durante o treinamento de modelos. Pode gerar textos, imagens, vídeos, áudio e código.

### 2.2 LLMs

LLM significa **Large Language Model**. São modelos de linguagem treinados em grandes quantidades de dados e utilizados em tarefas como geração, resumo, tradução, perguntas e respostas e programação.

### 2.3 Tokens

Tokens são unidades utilizadas para representar o texto processado pelo modelo. Dependendo da tokenização, um token pode corresponder a uma palavra, parte de palavra ou pontuação.

### 2.4 Contexto

Contexto são as informações disponíveis para o modelo durante uma interação. Um prompt com objetivo, público, restrições e formato definidos tende a ser mais direcionado.

### 2.5 Transformers e atenção

Transformers são arquiteturas amplamente usadas em modelos modernos de linguagem. O mecanismo de atenção permite considerar relações entre diferentes partes de uma sequência para produzir representações e previsões mais adequadas.

### 2.6 Engenharia de Prompts

É o processo de criar, testar, avaliar e melhorar instruções para modelos de IA. Um bom prompt pode especificar objetivo, contexto, instruções, restrições, formato e exemplos.

### 2.7 RAG

**Retrieval-Augmented Generation (RAG)** combina recuperação de informações externas com geração de respostas. De forma simplificada: pergunta → busca → recuperação de trechos → contexto → geração.

### 2.8 Alucinações

Uma alucinação ocorre quando o modelo apresenta informação falsa, inventada ou sem sustentação como se fosse verdadeira. Por isso, informações importantes devem ser verificadas e, quando possível, vinculadas a fontes.

### 2.9 Viés

Modelos podem refletir padrões ou vieses presentes nos dados de desenvolvimento. O contexto de aplicação, a qualidade dos dados e a avaliação humana são importantes para reduzir impactos inadequados.

### 2.10 Uso responsável

O uso responsável considera precisão, segurança, privacidade, transparência, vieses, propriedade intelectual, impactos sociais e supervisão humana.

## 🧪 3. Engenharia de Prompts e testes

### Teste 1 — Prompt amplo

> O que é Inteligência Artificial Generativa?

**Objetivo:** obter uma definição inicial.

**Problema:** muito aberto; pode resultar em resposta superficial ou fora do nível desejado.

### Teste 2 — Prompt contextualizado

> Explique o que é Inteligência Artificial Generativa para um estudante de Ciência da Computação. Apresente definição, funcionamento básico, exemplos, principais tecnologias e limitações. Organize em tópicos e use linguagem didática.

**Melhoria:** adiciona público, escopo e formato.

### Teste 3 — Prompt baseado nas fontes

> Utilize exclusivamente as fontes disponíveis neste notebook para explicar Inteligência Artificial Generativa. Divida a resposta em definição, funcionamento, exemplos, relação com LLMs, limitações e uso responsável. Para cada seção, indique a fonte que sustenta a informação. Caso algo não esteja presente nas fontes, informe explicitamente que não foi encontrado.

**Melhoria:** aumenta rastreabilidade e reduz extrapolação.

### Teste 4 — Comparação

> Com base exclusivamente nas fontes deste notebook, compare LLM, IA Generativa e RAG. Apresente definição, objetivo, funcionamento, relação entre os conceitos, exemplo prático e principal limitação. Organize em tabela.

**Objetivo:** testar compreensão das relações entre conceitos.

### Teste 5 — Aprendizagem ativa

> Atue como um professor de Ciência da Computação. Faça uma pergunta por vez sobre Inteligência Artificial Generativa. Não mostre a resposta antes que eu tente responder. Depois avalie minha resposta, corrija erros, explique o conceito e faça uma nova pergunta com dificuldade progressiva. Utilize as fontes disponíveis como base.

**Objetivo:** transformar a IA em ferramenta de estudo ativo.

## 🩹 4. Cicatrizes / Troubleshooting

| Problema | Possível causa | Solução |
|---|---|---|
| Resposta genérica | Prompt aberto | Adicionar contexto |
| Resposta superficial | Objetivo pouco definido | Especificar profundidade |
| Muitos assuntos | Escopo amplo | Definir tópicos |
| Resposta extensa | Formato não definido | Definir tamanho/estrutura |
| Sem referências | Fontes não exigidas | Pedir rastreabilidade |
| Informação ausente | Fonte insuficiente | Adicionar fonte |
| Conceito difícil | Público não definido | Definir nível do estudante |
| Possível alucinação | Extrapolação | Restringir às fontes |

O processo de refinamento foi:

```text
Pergunta → Resposta → Avaliação crítica → Problema → Refinamento → Nova resposta → Comparação
```

## 📖 5. Glossário

| Termo | Definição |
|---|---|
| IA | Inteligência Artificial. |
| IA Generativa | IA capaz de gerar novos conteúdos. |
| LLM | Large Language Model, modelo de linguagem de grande escala. |
| Token | Unidade usada para representar partes do texto. |
| Contexto | Informações disponíveis ao modelo durante uma interação. |
| Prompt | Instrução fornecida ao modelo. |
| Engenharia de Prompts | Criação e otimização de instruções para IA. |
| Transformer | Arquitetura de rede neural usada em muitos modelos modernos. |
| Atenção | Mecanismo que considera relações entre elementos de uma sequência. |
| Embedding | Representação numérica de dados em espaço vetorial. |
| RAG | Retrieval-Augmented Generation. |
| Alucinação | Informação incorreta ou inventada apresentada de modo plausível. |
| Viés | Tendência sistemática que pode gerar resultados distorcidos. |
| Fine-tuning | Adaptação de modelo pré-treinado para uma finalidade. |
| Inferência | Uso do modelo treinado para produzir uma saída. |

## ♻️ 6. Prompts reutilizáveis

Os prompts completos estão em [`materiais/prompts.md`](materiais/prompts.md).

Exemplos:

### Explicação

> Explique [CONCEITO] para um estudante de Ciência da Computação que está começando a estudar o assunto. Apresente definição, funcionamento, exemplo, aplicação e limitações. Finalize com 5 pontos essenciais.

### Resumo

> Resuma as fontes disponíveis sobre [TEMA]. Organize em conceitos fundamentais, conceitos intermediários, exemplos, aplicações e limitações. Não adicione informações não sustentadas pelas fontes.

### Validação

> Analise a resposta abaixo usando exclusivamente as fontes disponíveis. Classifique cada afirmação como sustentada, parcialmente sustentada ou não encontrada.

## 📊 7. Critérios de avaliação

As respostas podem ser avaliadas de 1 a 5 nos seguintes critérios:

- Precisão
- Aderência às fontes
- Clareza
- Organização
- Profundidade
- Utilidade para estudo
- Rastreabilidade

## 🚀 8. Melhorias futuras

O projeto pode ser expandido com:

- Agentes de IA;
- embeddings;
- bancos vetoriais;
- fine-tuning;
- avaliação de LLMs;
- segurança de aplicações de IA;
- prompt injection;
- agentes autônomos;
- IA multimodal.

## 🏁 9. Conclusão

O projeto mostrou que utilizar IA para estudar não significa apenas solicitar respostas prontas. Um processo mais eficiente envolve **curadoria → pergunta → resposta → avaliação → refinamento → validação → síntese**.

O NotebookLM pode apoiar esse processo ao trabalhar com um conjunto definido de fontes, enquanto o GitHub permite documentar e apresentar o resultado como portfólio.

O principal aprendizado foi compreender que respostas de IA precisam ser analisadas criticamente. A qualidade das fontes, a formulação do prompt, o contexto e a validação humana continuam sendo fundamentais.

## 📂 Estrutura do repositório

```text
miniguia-ia-generativa-notebooklm/
├── README.md
├── fontes/
│   └── fontes.md
└── materiais/
    └── prompts.md
```

## 👨‍💻 Autor

**Gustavo Rodrigues**  
Estudante de Ciência da Computação.

Projeto desenvolvido para fins educacionais e de portfólio como parte do desafio da DIO sobre Inteligência Artificial como ferramenta de aprendizagem ativa.
