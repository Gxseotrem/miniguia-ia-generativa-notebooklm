# 🤖 Miniguia de Inteligência Artificial Generativa com NotebookLM

![Status](https://img.shields.io/badge/status-concluído-brightgreen)
![Tema](https://img.shields.io/badge/tema-IA%20Generativa-blue)
![Ferramenta](https://img.shields.io/badge/ferramenta-NotebookLM-orange)

> Projeto desenvolvido como parte do desafio da DIO sobre aprendizagem ativa com Inteligência Artificial e uso do NotebookLM.

---

## 📚 Sobre o projeto

Este projeto apresenta um **Caderno Temático sobre Inteligência Artificial Generativa**, desenvolvido com apoio do **NotebookLM** como ferramenta de aprendizagem ativa.

A proposta foi utilizar a Inteligência Artificial não apenas para obter respostas prontas, mas como ferramenta para pesquisar, organizar informações, comparar fontes, formular perguntas, testar prompts, identificar limitações e consolidar conhecimentos.

O material foi organizado em um repositório no GitHub para servir como registro do processo de aprendizagem e também como parte do meu portfólio acadêmico e profissional.

---

## 🎯 Contexto e objetivos

A Inteligência Artificial Generativa vem ganhando espaço em áreas como desenvolvimento de software, educação, pesquisa, produção de conteúdo e análise de informações.

O objetivo deste projeto foi estudar os principais conceitos relacionados à IA Generativa por meio de fontes abertas e utilizar o NotebookLM para organizar, consultar e consolidar esse conhecimento.

### Objetivos específicos

- Compreender o conceito de Inteligência Artificial Generativa;
- Entender o funcionamento dos Large Language Models (LLMs);
- Compreender tokens, contexto, Transformers e mecanismo de atenção;
- Estudar Engenharia de Prompts;
- Entender o funcionamento do RAG;
- Identificar limitações e riscos da IA Generativa;
- Desenvolver uma abordagem crítica para utilização de ferramentas de IA;
- Criar prompts reutilizáveis para estudos futuros.

---

## 🧰 Ferramentas utilizadas

- **NotebookLM** — organização das fontes, consultas e aprendizagem baseada em documentos;
- **GitHub** — documentação e armazenamento do projeto;
- **Markdown** — organização e documentação do conhecimento;
- **Inteligência Artificial Generativa** — utilizada como ferramenta de apoio ao processo de aprendizagem.

---

# 🔎 Curadoria das fontes

Para desenvolver o Caderno Temático, foram selecionadas fontes abertas relacionadas à Inteligência Artificial Generativa, modelos de linguagem, Engenharia de Prompts, RAG e uso responsável de IA.

As fontes foram adicionadas ao NotebookLM para que as consultas e análises fossem realizadas com base no material selecionado.

As fontes utilizadas estão documentadas em:

📁 [`fontes/fontes.md`](fontes/fontes.md)

Entre as principais referências utilizadas estão materiais de:

- IBM;
- NIST — National Institute of Standards and Technology;
- Google Cloud;
- Google Developers;
- Lewis et al. — trabalho acadêmico sobre Retrieval-Augmented Generation (RAG).

---

# 🧪 Engenharia de Prompts e testes realizados

Durante o desenvolvimento do projeto, foram realizados testes com diferentes prompts no NotebookLM.

O processo utilizado foi:

**Perguntar → analisar → identificar limitações → refinar → testar novamente.**

---

## 🧪 Teste 1 — Introdução à IA Generativa

### Prompt utilizado

> O que é Inteligência Artificial Generativa? Explique para um estudante de Ciência da Computação que está começando a estudar o assunto. Apresente uma definição, explique como funciona, dê exemplos de aplicações e apresente suas principais limitações. Utilize as fontes disponíveis neste notebook.

### Resultado resumido

A resposta apresentou a IA Generativa como uma área da Inteligência Artificial capaz de criar novos conteúdos, como textos, imagens, vídeos, áudios e códigos.

Também explicou conceitos relacionados ao funcionamento da tecnologia, incluindo Deep Learning, tokens, Transformers, treinamento, fine-tuning e RLHF.

Foram apresentadas aplicações em desenvolvimento de software, geração de imagens e vídeos, ciência, medicina e personalização.

A resposta também destacou riscos como alucinações, vieses, segurança, privacidade, propriedade intelectual e impacto ambiental.

### 💡 Aprendizado

A IA Generativa não apenas processa informações existentes, mas pode criar novos conteúdos a partir dos padrões aprendidos durante seu treinamento.

Também foi possível perceber que a tecnologia possui limitações e exige validação e utilização responsável.

---

# 🧪 Teste 2 — LLMs, Tokens, Contexto e Transformers

### Prompt utilizado

> Explique o que são Large Language Models (LLMs). Explique também o que são tokens, contexto, Transformers e mecanismo de atenção. Utilize exclusivamente as fontes disponíveis neste notebook e apresente a resposta de maneira didática.

### Resultado resumido

A resposta explicou que os **LLMs** são modelos treinados com grandes quantidades de texto para aprender padrões da linguagem.

Também foram explicados:

- Tokens;
- Contexto;
- Transformers;
- Self-attention.

Os tokens foram apresentados como unidades utilizadas pelos modelos para processar textos, enquanto o contexto representa as informações utilizadas para interpretar uma sequência.

Os Transformers foram apresentados como uma arquitetura fundamental dos LLMs modernos, utilizando mecanismos de atenção para identificar relações importantes entre diferentes partes de uma sequência.

### 💡 Aprendizado

LLMs não trabalham simplesmente com palavras isoladas. Eles processam **tokens dentro de um contexto**, utilizando arquiteturas como Transformers e mecanismos de atenção para compreender relações entre diferentes elementos do texto.

---

# 🧪 Teste 3 — Engenharia de Prompts

### Prompt utilizado

> Explique o conceito de Engenharia de Prompts. Mostre quais elementos podem fazer parte de um prompt bem estruturado e explique por que contexto, objetivo, restrições e formato de saída são importantes. Utilize as fontes disponíveis neste notebook.

### Resultado resumido

A resposta apresentou a Engenharia de Prompts como um processo de criação, teste e refinamento de instruções para obter respostas mais úteis e precisas dos modelos de linguagem.

Entre os elementos apresentados estão:

- Objetivo;
- Instruções;
- Persona;
- Contexto;
- Restrições;
- Exemplos;
- Tom;
- Formato de saída.

A resposta destacou especialmente a importância do objetivo, contexto, restrições e formato de saída.

### 💡 Aprendizado

Um prompt eficiente não deve apenas apresentar uma pergunta. É importante fornecer **contexto, objetivo, instruções e critérios para a resposta**, aumentando o controle sobre o resultado produzido pela IA.

---

# 🧪 Teste 4 — Retrieval-Augmented Generation (RAG)

### Prompt utilizado

> Explique o conceito de Retrieval-Augmented Generation (RAG). Explique como funciona o processo de recuperação de informações e geração da resposta. Utilize principalmente a fonte acadêmica de Lewis et al. e explique o conceito em linguagem adequada para um estudante iniciante.

### Resultado resumido

A resposta explicou o **RAG** como uma técnica que combina o conhecimento aprendido pelo modelo com informações recuperadas de fontes externas.

O processo foi dividido em:

1. Consulta;
2. Recuperação de documentos relevantes;
3. Geração da resposta.

Também foram apresentados os conceitos de:

- Memória paramétrica;
- Memória não paramétrica;
- Retriever;
- Generator.

A resposta destacou que o RAG pode contribuir para reduzir alucinações, aumentar a transparência e facilitar a utilização de informações externas.

### 💡 Aprendizado

O RAG permite conectar modelos de linguagem a **fontes externas de conhecimento**, possibilitando respostas baseadas em informações recuperadas de documentos específicos.

---

# 🧪 Teste 5 — Riscos da IA Generativa

### Prompt utilizado

> Quais são os principais riscos associados à Inteligência Artificial Generativa? Explique conceitos como alucinação, viés, privacidade, segurança e confiabilidade. Utilize as fontes disponíveis neste notebook, especialmente o material do NIST.

### Resultado resumido

A resposta apresentou diversos riscos relacionados à IA Generativa, com destaque para:

- Confabulação ou alucinação;
- Viés prejudicial;
- Homogeneização;
- Privacidade;
- Segurança da informação;
- Prompt Injection;
- Data Poisoning;
- Confiabilidade;
- Impacto ambiental;
- Propriedade intelectual.

Também foram discutidos problemas relacionados à memorização de informações pessoais e à utilização da IA em situações de risco.

### 💡 Aprendizado

O uso de IA Generativa exige **pensamento crítico e responsabilidade**, pois os modelos podem produzir informações incorretas, enviesadas ou potencialmente prejudiciais.

Informações importantes devem ser verificadas antes de serem utilizadas.

---

# 🧪 Teste 6 — Refinamento do Prompt

### Prompt utilizado

> Utilize exclusivamente as fontes disponíveis neste notebook para explicar Inteligência Artificial Generativa.
>
> Divida a resposta em:
>
> 1. definição;
> 2. funcionamento;
> 3. LLMs;
> 4. Engenharia de Prompts;
> 5. RAG;
> 6. limitações;
> 7. uso responsável.
>
> Para cada seção, indique qual fonte sustenta a informação.
> Caso uma informação não esteja presente nas fontes, informe que ela não foi encontrada.

### Resultado resumido

A resposta apresentou uma explicação estruturada em sete partes:

1. Definição;
2. Funcionamento;
3. LLMs;
4. Engenharia de Prompts;
5. RAG;
6. Limitações e riscos;
7. Uso responsável.

Também foram relacionadas diferentes fontes aos conceitos apresentados, incluindo IBM, NIST, Google Cloud, Google Developers e Lewis et al.

### 💡 Aprendizado

O teste demonstrou que um prompt contendo **escopo, estrutura, restrições e critérios de validação** consegue produzir uma resposta mais organizada e direcionada.

A exigência de utilizar exclusivamente as fontes também reforçou a importância da rastreabilidade das informações.

---

# 🩹 Cicatrizes / Troubleshooting

Durante os testes, alguns aprendizados importantes foram identificados sobre a construção de prompts.

## Cicatriz 1 — Perguntas muito amplas

Perguntas muito abertas podem produzir respostas abrangentes, mas nem sempre adequadas ao objetivo específico do estudo.

### Solução

Adicionar:

- Contexto;
- Objetivo;
- Público-alvo;
- Tópicos específicos;
- Formato desejado.

---

## Cicatriz 2 — Necessidade de organização

Quando vários conceitos são solicitados simultaneamente, a resposta pode ficar extensa ou pouco organizada.

### Solução

Dividir a solicitação em tópicos e definir previamente a estrutura da resposta.

---

## Cicatriz 3 — Necessidade de rastreabilidade

Para estudos baseados em fontes, é importante saber de onde as informações apresentadas foram retiradas.

### Solução

Solicitar que a resposta seja baseada nas fontes disponíveis e, quando possível, indicar qual fonte sustenta cada informação.

---

## Cicatriz 4 — Controle das informações

Uma resposta de IA pode apresentar informações que não estão presentes nas fontes utilizadas.

### Solução

Adicionar uma restrição explícita:

> "Caso uma informação não esteja presente nas fontes, informe que ela não foi encontrada."

---

## 💡 Principal aprendizado dos testes

O principal aprendizado foi perceber que **a qualidade da resposta depende também da qualidade da instrução fornecida ao modelo**.

O processo de refinamento pode ser representado por:

**Prompt inicial → Teste → Análise → Refinamento → Novo teste → Resultado**

---

# 📖 Miniguia de Estudo

## 1. O que é Inteligência Artificial Generativa?

IA Generativa é uma área da Inteligência Artificial voltada à criação de novos conteúdos a partir de padrões aprendidos em grandes volumes de dados.

Ela pode ser utilizada para gerar:

- Textos;
- Imagens;
- Vídeos;
- Áudios;
- Código;
- Outros tipos de conteúdo.

---

## 2. O que são LLMs?

**LLM (Large Language Model)** é um modelo de linguagem treinado com grandes quantidades de texto para aprender padrões e relações da linguagem.

Esses modelos trabalham com tokens e utilizam o contexto disponível para gerar respostas.

---

## 3. O que são Tokens?

Tokens são unidades utilizadas pelos modelos de linguagem para representar e processar textos.

Um token pode representar:

- Uma palavra;
- Parte de uma palavra;
- Um caractere;
- Outros fragmentos de texto.

---

## 4. O que são Transformers?

Transformers são uma arquitetura de Deep Learning utilizada em muitos modelos modernos de linguagem.

Uma de suas principais características é o mecanismo de atenção, que permite analisar relações entre diferentes partes de uma sequência.

---

## 5. O que é Engenharia de Prompts?

É o processo de criação e refinamento de instruções para orientar modelos de IA a produzir respostas mais adequadas.

Um prompt pode utilizar:

**Objetivo + Contexto + Instruções + Restrições + Formato de saída**

---

## 6. O que é RAG?

**Retrieval-Augmented Generation** é uma técnica que permite ao sistema recuperar informações de fontes externas antes de gerar uma resposta.

Fluxo simplificado:

```text
Pergunta
   ↓
Busca por informações relevantes
   ↓
Recuperação de documentos
   ↓
Modelo de linguagem
   ↓
Resposta baseada nas informações recuperadas
