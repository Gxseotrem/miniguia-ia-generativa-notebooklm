# 🧪 Engenharia de Prompts — Registro de testes

## 🎯 Objetivo

Documentar os prompts utilizados durante o desenvolvimento do Caderno Temático no NotebookLM, registrando o processo de elaboração, teste, análise e refinamento das perguntas.

O objetivo foi utilizar a IA como ferramenta de aprendizagem ativa, buscando compreender conceitos de Inteligência Artificial Generativa a partir das fontes selecionadas.

---

# 🧪 Teste 01 — Introdução à IA Generativa

### Prompt

> O que é Inteligência Artificial Generativa? Explique para um estudante de Ciência da Computação que está começando a estudar o assunto. Apresente uma definição, explique como funciona, dê exemplos de aplicações e apresente suas principais limitações. Utilize as fontes disponíveis neste notebook.

### Objetivo

Compreender o conceito inicial de Inteligência Artificial Generativa, seu funcionamento, aplicações e limitações.

### Resultado

A resposta apresentou conceitos fundamentais sobre IA Generativa, incluindo Deep Learning, tokens, Transformers, treinamento, aplicações e principais riscos.

### Aprendizado

Foi possível compreender a diferença entre IA tradicional e IA Generativa e identificar suas principais aplicações e limitações.

---

# 🧪 Teste 02 — LLMs, Tokens, Contexto e Transformers

### Prompt

> Explique o que são Large Language Models (LLMs). Explique também o que são tokens, contexto, Transformers e mecanismo de atenção. Utilize exclusivamente as fontes disponíveis neste notebook e apresente a resposta de maneira didática.

### Objetivo

Compreender os principais componentes técnicos relacionados aos modelos de linguagem modernos.

### Resultado

A resposta explicou LLMs, tokens, contexto, Transformers e mecanismo de self-attention.

### Aprendizado

Foi possível compreender que os modelos de linguagem processam tokens dentro de um contexto e utilizam arquiteturas como Transformers para identificar relações entre diferentes partes de uma sequência.

---

# 🧪 Teste 03 — Engenharia de Prompts

### Prompt

> Explique o conceito de Engenharia de Prompts. Mostre quais elementos podem fazer parte de um prompt bem estruturado e explique por que contexto, objetivo, restrições e formato de saída são importantes. Utilize as fontes disponíveis neste notebook.

### Objetivo

Compreender como a estrutura de um prompt influencia a qualidade e a organização das respostas geradas pela IA.

### Resultado

A resposta apresentou elementos como objetivo, instruções, persona, contexto, restrições, exemplos, tom e formato de saída.

### Aprendizado

Foi possível perceber que prompts mais claros e estruturados oferecem maior controle sobre o resultado produzido pelo modelo.

---

# 🧪 Teste 04 — Retrieval-Augmented Generation (RAG)

### Prompt

> Explique o conceito de Retrieval-Augmented Generation (RAG). Explique como funciona o processo de recuperação de informações e geração da resposta. Utilize principalmente a fonte acadêmica de Lewis et al. e explique o conceito em linguagem adequada para um estudante iniciante.

### Objetivo

Compreender o funcionamento do RAG e sua relação com modelos de linguagem.

### Resultado

A resposta explicou o processo de recuperação de documentos e geração de respostas, apresentando os conceitos de memória paramétrica, memória não paramétrica, retriever e generator.

### Aprendizado

Foi possível compreender como o RAG permite utilizar informações externas para complementar o conhecimento de um modelo de linguagem.

---

# 🧪 Teste 05 — Riscos da IA Generativa

### Prompt

> Quais são os principais riscos associados à Inteligência Artificial Generativa? Explique conceitos como alucinação, viés, privacidade, segurança e confiabilidade. Utilize as fontes disponíveis neste notebook, especialmente o material do NIST.

### Objetivo

Identificar os principais riscos relacionados ao desenvolvimento e utilização de sistemas de IA Generativa.

### Resultado

A resposta apresentou riscos como confabulação/alucinação, viés, homogeneização, privacidade, prompt injection, data poisoning, confiabilidade, impacto ambiental e propriedade intelectual.

### Aprendizado

Foi possível compreender que a utilização da IA Generativa exige avaliação crítica, validação das informações e preocupação com segurança, privacidade e uso responsável.

---

# 🧪 Teste 06 — Refinamento e validação por fontes

### Prompt

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

### Objetivo

Testar um prompt mais estruturado, com restrições, organização por tópicos e exigência de rastreabilidade das informações.

### Resultado

A resposta apresentou uma explicação dividida em sete seções e relacionou os conceitos às fontes utilizadas no notebook.

### Aprendizado

O teste demonstrou que a definição de escopo, estrutura, restrições e critérios de validação contribui para respostas mais organizadas e direcionadas.

---

# 🩹 Cicatrizes / Troubleshooting

Durante os testes, foram identificados alguns pontos que influenciaram a qualidade das respostas.

| Problema | Possível causa | Solução |
|---|---|---|
| Resposta superficial | Pouco contexto | Definir o nível do estudante |
| Resposta genérica | Pergunta muito aberta | Especificar o objetivo |
| Muitos assuntos | Escopo amplo | Dividir o conteúdo em tópicos |
| Resposta desorganizada | Formato não definido | Especificar a estrutura |
| Falta de rastreabilidade | Fontes não exigidas | Solicitar indicação das fontes |
| Informação não encontrada | Fonte insuficiente | Adicionar ou substituir fontes |
| Conceito difícil | Linguagem inadequada | Solicitar explicação didática |
| Possível alucinação | Extrapolação do modelo | Restringir a resposta às fontes |

---

# 🔄 Processo de refinamento

O processo utilizado durante o projeto pode ser representado da seguinte maneira:

```text
Prompt
   ↓
Resposta
   ↓
Análise crítica
   ↓
Identificação de problemas
   ↓
Refinamento do prompt
   ↓
Novo teste
   ↓
Comparação dos resultados
