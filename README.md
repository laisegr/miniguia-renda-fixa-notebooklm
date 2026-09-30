# Miniguia de Renda Fixa com NotebookLM

Projeto desenvolvido como parte de um desafio da DIO, com o objetivo de explorar o uso da Inteligência Artificial como ferramenta de aprendizagem ativa.

Neste projeto, o NotebookLM será utilizado para organizar e analisar fontes confiáveis sobre renda fixa, permitindo testar diferentes estratégias de prompts, comparar respostas e consolidar o aprendizado em um miniguia de estudos.

## 📌 Tema

**Renda Fixa para Iniciantes: conceitos, riscos e principais tipos de investimento**

A escolha do tema busca reunir conceitos fundamentais para quem está começando a estudar investimentos, utilizando fontes abertas e confiáveis como base para a construção do conhecimento.

## 🎯 Objetivos de estudo

- Compreender o conceito de renda fixa;
- Diferenciar investimentos prefixados, pós-fixados e híbridos;
- Entender conceitos como rentabilidade, liquidez, prazo e risco;
- Conhecer os principais tipos de títulos do Tesouro Direto;
- Identificar diferenças entre Tesouro Selic, Tesouro Prefixado e Tesouro IPCA+;
- Utilizar o NotebookLM para sintetizar, revisar e organizar as informações das fontes selecionadas.

## 📚 Curadoria de fontes

Para a construção do caderno temático no NotebookLM, foram selecionadas fontes abertas e institucionais, priorizando conteúdos introdutórios e confiáveis sobre educação financeira, renda fixa, risco e títulos públicos.

### Fontes selecionadas

1. **Banco Central do Brasil — Caderno de Educação Financeira: Gestão de Finanças Pessoais**  
   Material introdutório sobre educação financeira, planejamento, poupança e investimentos.  
   https://www.bcb.gov.br/content/cidadaniafinanceira/documentos_cidadania/Cuidando_do_seu_dinheiro_Gestao_de_Financas_Pessoais/caderno_cidadania_financeira.pdf

2. **Portal do Investidor — Renda Fixa x Renda Variável**  
   Conteúdo utilizado para compreender o conceito de renda fixa e as diferenças entre remuneração prefixada, pós-fixada e híbrida.  
   https://www.gov.br/investidor/pt-br/investir/antes-de-investir/entenda-as-caracteristicas-dos-investimentos/renda-fixa-x-renda-variavel

3. **Portal do Investidor — Títulos Públicos**  
   Fonte utilizada para conhecer as características dos principais títulos públicos disponíveis, como Tesouro Selic, Tesouro Prefixado e Tesouro IPCA+.  
   https://www.gov.br/investidor/pt-br/investir/tipos-de-investimentos/titulos-publicos

4. **Portal do Investidor — Risco e a relação risco x retorno**  
   Material utilizado para estudar risco de crédito, risco de mercado, risco de liquidez e a relação entre risco e retorno nos investimentos.  
   https://www.gov.br/investidor/pt-br/investir/antes-de-investir/entenda-as-caracteristicas-dos-investimentos/risco-e-a-relacao-risco-x-retorno


## 🧠 Engenharia de prompts e aprendizados

Durante o uso do NotebookLM, foram testadas diferentes formas de formular as perguntas para observar como pequenas alterações nas instruções poderiam modificar a organização e a profundidade das respostas.

### Teste 1 — Prompt aberto

**Prompt utilizado:**

> Explique renda fixa para uma pessoa que nunca investiu.

**Resultado observado:**

O NotebookLM apresentou uma explicação clara e didática, abordando o conceito de renda fixa, formas de remuneração, principais títulos e riscos. Apesar da boa qualidade da resposta, a seleção dos conteúdos e a estrutura ficaram totalmente a cargo da IA.

**Aprendizado:**

O teste mostrou que um prompt simples pode produzir uma resposta satisfatória, mas oferece pouco controle sobre a organização, a profundidade e o formato do material.

### Teste 2 — Prompt estruturado

**Prompt utilizado:**

> Com base exclusivamente nas fontes deste notebook, explique renda fixa para uma pessoa que nunca investiu.
>
> Organize a resposta em:
> 1. conceito de renda fixa;
> 2. diferença entre investimentos prefixados, pós-fixados e híbridos;
> 3. principais tipos de títulos mencionados nas fontes;
> 4. riscos envolvidos;
> 5. resumo final com os cinco pontos mais importantes para revisão.
>
> Use linguagem simples e didática, mas preserve os termos técnicos essenciais. Não inclua informações que não estejam presentes nas fontes e mantenha as referências utilizadas.

**Resultado observado:**

A resposta passou a seguir uma estrutura previsível e alinhada aos objetivos do estudo. O conteúdo foi dividido nos cinco tópicos solicitados e terminou com uma síntese voltada à revisão.

**Cicatriz / dificuldade encontrada:**

O aumento do nível de detalhamento do prompt melhorou a organização e a precisão da resposta, mas também gerou um conteúdo mais extenso. Isso mostrou a necessidade de equilibrar profundidade e concisão de acordo com a finalidade do material.

**Aprendizado:**

Instruções sobre fonte, público-alvo, estrutura, linguagem e formato de saída tornam o resultado mais consistente. Ao mesmo tempo, prompts muito abrangentes podem produzir respostas maiores do que o necessário.


### Teste 3 — Refinamento para revisão rápida

**Prompt utilizado:**

> Com base exclusivamente nas fontes deste notebook, crie um resumo de revisão sobre renda fixa para um iniciante.
>
> Limite a resposta a no máximo 400 palavras e organize em:
> - conceito;
> - prefixado, pós-fixado e híbrido;
> - principais títulos;
> - riscos;
> - 5 palavras-chave para memorizar.
>
> Priorize apenas as informações essenciais para uma revisão rápida, sem repetir conceitos e sem acrescentar informações externas às fontes.

**Resultado observado:**

O NotebookLM produziu uma resposta mais concisa, mantendo os principais conceitos identificados nas fontes. O conteúdo permaneceu dividido por assunto e terminou com cinco palavras-chave para memorização, tornando o material mais adequado para uma revisão rápida.

**Melhoria em relação ao teste anterior:**

A limitação de tamanho e a instrução para evitar repetições reduziram o excesso de detalhamento observado no segundo teste, sem eliminar os conceitos essenciais para o objetivo de estudo.

**Aprendizado:**

Definir não apenas o conteúdo desejado, mas também o tamanho, a finalidade e o formato da resposta ajuda a adaptar o uso da IA a diferentes momentos do aprendizado. Um mesmo tema pode exigir uma resposta aprofundada para estudo inicial e uma versão mais curta para revisão.
