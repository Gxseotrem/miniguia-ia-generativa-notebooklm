# 🧪 Engenharia de Prompts — Registro de testes

## Objetivo

Documentar a evolução dos prompts utilizados no NotebookLM e demonstrar o processo de tentativa, avaliação e refinamento.

---

## Teste 01 — Pergunta aberta

**Prompt:**

> O que é Inteligência Artificial Generativa?

**Objetivo:** obter uma definição inicial.

**Problema esperado:** pergunta ampla, podendo gerar resposta genérica.

**Aprendizado:** adicionar contexto, público e formato pode tornar a resposta mais útil.

---

## Teste 02 — Prompt contextualizado

**Prompt:**

> Explique o que é Inteligência Artificial Generativa para um estudante de Ciência da Computação. Apresente definição, funcionamento básico, exemplos de aplicação, tecnologias envolvidas e limitações. Organize a resposta em tópicos e use linguagem didática.

**Melhoria:** define público, escopo e formato.

---

## Teste 03 — Prompt baseado nas fontes

**Prompt:**

> Utilize exclusivamente as fontes disponíveis neste notebook para explicar Inteligência Artificial Generativa. Divida a resposta em definição, funcionamento, exemplos, relação com LLMs, limitações e uso responsável. Para cada seção, indique qual fonte sustenta a informação. Caso uma informação não esteja presente nas fontes, informe explicitamente que ela não foi encontrada.

**Melhoria:** adiciona rastreabilidade e reduz extrapolações.

---

## Teste 04 — Comparação de conceitos

**Prompt:**

> Com base exclusivamente nas fontes deste notebook, compare LLM, IA Generativa e RAG. Apresente definição, objetivo, funcionamento, relação entre os conceitos, exemplo prático e principal limitação. Organize em tabela e finalize com uma explicação simples de como os três podem aparecer juntos em uma aplicação real.

**Objetivo:** verificar compreensão das relações entre conceitos.

---

## Teste 05 — Aprendizagem ativa

**Prompt:**

> Atue como um professor de Ciência da Computação. Faça uma pergunta por vez sobre Inteligência Artificial Generativa. Não mostre a resposta antes que eu tente responder. Depois avalie minha resposta, corrija erros, explique o conceito e faça uma nova pergunta aumentando gradualmente a dificuldade. Utilize as fontes disponíveis neste notebook como base.

**Objetivo:** utilizar a IA como tutora e não apenas como geradora de resumos.

---

# 🩹 Troubleshooting

| Sintoma | Diagnóstico | Ajuste |
|---|---|---|
| Resposta superficial | Pouco contexto | Definir nível do estudante |
| Resposta genérica | Prompt aberto | Especificar objetivo |
| Muitos assuntos | Escopo amplo | Delimitar tópicos |
| Resposta longa | Formato não definido | Definir tamanho/estrutura |
| Sem evidências | Fontes não exigidas | Pedir referências |
| Informação ausente | Fonte insuficiente | Adicionar ou substituir fonte |
| Conceito difícil | Linguagem inadequada | Pedir explicação progressiva |
| Possível alucinação | Extrapolação do modelo | Restringir às fontes |

## Processo de refinamento

```text
Prompt
  ↓
Resposta
  ↓
Avaliação crítica
  ↓
Identificação do problema
  ↓
Refinamento
  ↓
Nova resposta
  ↓
Comparação
```

---

# ♻️ Biblioteca de prompts reutilizáveis

## 1. Explicação de conceito

> Explique [CONCEITO] para um estudante de Ciência da Computação que está começando a estudar o assunto. Apresente definição, funcionamento, exemplo prático, aplicação e limitações. Finalize com 5 pontos essenciais para memorizar.

## 2. Resumo

> Resuma as fontes disponíveis sobre [TEMA]. Organize em conceitos fundamentais, conceitos intermediários, exemplos, aplicações e limitações. Não adicione informações que não estejam sustentadas pelas fontes.

## 3. Comparação

> Compare [CONCEITO A] e [CONCEITO B]. Apresente definição, objetivo, funcionamento, vantagens, limitações e exemplos. Organize em tabela e utilize exclusivamente as fontes disponíveis.

## 4. Revisão

> Crie uma revisão sobre [TEMA] contendo 10 perguntas de múltipla escolha. Não apresente as respostas inicialmente. Depois que eu responder, corrija minhas respostas, explique os erros, indique os assuntos que devo revisar e atribua uma nota de 0 a 10.

## 5. Método socrático

> Atue como um professor de Ciência da Computação. Quero aprender [TEMA]. Faça uma pergunta por vez e não entregue a resposta imediatamente. Analise minha resposta, identifique acertos e erros, explique o conceito e faça uma nova pergunta com dificuldade progressiva.

## 6. Validação

> Analise a resposta abaixo utilizando exclusivamente as fontes disponíveis neste notebook. Classifique cada afirmação como: sustentada pelas fontes, parcialmente sustentada ou não encontrada. Não tente completar informações ausentes.

**Resposta:**

[COLE A RESPOSTA AQUI]

## 7. Preparação para entrevista

> Simule uma entrevista técnica sobre [TEMA] para uma vaga de estágio em tecnologia. Faça uma pergunta por vez. Depois da minha resposta, avalie precisão técnica, clareza, domínio do conceito e capacidade de fornecer exemplos. Dê uma nota de 0 a 10 e indique como melhorar.

---

# 📊 Critérios de avaliação

Avalie cada resposta de 1 a 5 em:

- Precisão;
- Aderência às fontes;
- Clareza;
- Organização;
- Profundidade;
- Utilidade para estudo;
- Rastreabilidade.
