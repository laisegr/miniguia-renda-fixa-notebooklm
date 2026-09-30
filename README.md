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

### Evidências dos testes

As respostas obtidas nos testes foram geradas pelo NotebookLM a partir das quatro fontes apresentadas na seção de curadoria.

Ao longo dos testes, foram observadas três formas diferentes de resposta:

- **Teste 1:** resposta ampla e didática, com organização definida pela própria IA;
- **Teste 2:** resposta estruturada conforme os tópicos solicitados, com maior nível de detalhamento;
- **Teste 3:** resposta mais concisa e direcionada à revisão rápida, preservando os conceitos essenciais.

As referências apresentadas pelo NotebookLM em cada resposta remetem às fontes adicionadas ao caderno temático e listadas neste repositório.

## 📖 Miniguia de Estudo

### 1. O que é Renda Fixa

A **renda fixa** é uma classe de investimentos que paga, em períodos definidos, uma remuneração correspondente a uma determinada taxa de juros. Ao aplicar em renda fixa, o investidor assume o papel de **credor**, emprestando seu dinheiro para uma instituição **devedora** — como o Governo Federal, bancos ou empresas de capital aberto.

Em troca desse empréstimo, a instituição emissora assume o compromisso de devolver a quantia aplicada (o principal) acrescida de juros no vencimento do título. Todas as regras de remuneração, prazos, formas de cálculo e índices envolvidos são combinados e acertados no momento da aplicação.

### 2. Como funciona a rentabilidade

A forma de cálculo dos rendimentos em renda fixa pode ser dividida em três modalidades:

- **Prefixada:** a taxa de juros é totalmente fixada no momento da aplicação. Com isso, o investidor já sabe exatamente o valor nominal que irá receber na data do vencimento.
- **Pós-fixada:** a rentabilidade final depende da variação de um indicador econômico ou taxa de referência apurada ao longo do período do investimento, como a **Taxa Selic** e a **Taxa DI/CDI**.
- **Híbrida:** combina uma taxa de juros prefixada com a variação de um índice oficial de inflação, como o **IPCA**.

### 3. Principais tipos de títulos

- **Títulos Públicos (Tesouro Direto):** emitidos pelo Governo Federal. Entre os exemplos apresentados nas fontes estão Tesouro Selic, Tesouro Reserva, Tesouro Prefixado, Tesouro IPCA+, Tesouro RendA+ e Tesouro Educa+.
- **Títulos Privados Bancários:** emitidos por instituições financeiras, como Caderneta de Poupança, CDBs, RDBs, RDCs, LCIs e LCAs.
- **Títulos Privados de Empresas e Securitizadoras:** incluem Debêntures, CRIs e CRAs.
- **Outras estruturas:** fundos de investimento em renda fixa e ETFs de renda fixa.

### 4. Principais riscos

- **Risco de Crédito:** possibilidade de a instituição emissora não cumprir suas obrigações de pagamento dos juros ou do principal. Aplicações bancárias específicas podem contar com proteção do FGC ou FGCoop, conforme os limites regulamentados.
- **Risco de Mercado:** alterações nas condições econômicas e nas taxas de juros podem provocar oscilações nos preços dos títulos antes do vencimento, fenômeno relacionado à marcação a mercado.
- **Risco de Liquidez:** dificuldade de converter o investimento em dinheiro disponível a um valor justo no momento desejado.
- **Riscos Legal e Operacional:** relacionados, respectivamente, a problemas jurídicos no título ou contrato e a falhas humanas, tecnológicas ou de gestão.

### 5. Pontos essenciais para revisão

1. Investir em renda fixa equivale a emprestar dinheiro a uma instituição em troca de juros.
2. A rentabilidade pode ser prefixada, pós-fixada ou híbrida.
3. Existem títulos emitidos pelo Governo Federal, instituições financeiras e empresas.
4. Renda fixa não significa ausência de riscos: crédito, mercado e liquidez devem ser considerados.
5. A venda de um título antes do vencimento pode sofrer os efeitos da marcação a mercado.

## 📚 Glossário dos principais conceitos

- **Renda Fixa:** modalidade de investimento em que as condições de remuneração, prazos e regras de rentabilidade são pactuadas no momento da aplicação.
- **Credor e Devedor:** o investidor atua como credor ao emprestar os recursos, enquanto a instituição emissora é a devedora.
- **Prefixado:** título cuja taxa de juros é determinada no momento da compra.
- **Pós-fixado:** investimento cuja rentabilidade depende da variação de um indicador econômico de referência.
- **Híbrido:** título que combina uma taxa fixa com a variação de um índice de inflação.
- **Taxa Selic:** taxa básica de juros da economia e referência utilizada em títulos pós-fixados.
- **Taxa DI/CDI:** referência utilizada em diversos títulos bancários pós-fixados.
- **IPCA:** índice de inflação utilizado como referência em investimentos híbridos.
- **Títulos Públicos:** títulos emitidos pelo Governo Federal e disponibilizados aos investidores por meio do Tesouro Direto.
- **Títulos Privados Bancários:** títulos emitidos por instituições financeiras, como CDBs, LCIs e LCAs.
- **Debêntures, CRIs e CRAs:** exemplos de títulos privados emitidos por empresas ou companhias securitizadoras.
- **Risco de Crédito:** possibilidade de o emissor não cumprir suas obrigações financeiras.
- **FGC:** mecanismo de proteção aplicável a determinadas aplicações bancárias, observados seus limites regulamentados.
- **Marcação a Mercado:** variação do preço de negociação de um título antes do vencimento.
- **Risco de Liquidez:** facilidade ou dificuldade de transformar o investimento em dinheiro a um valor justo.


## 🔁 Prompts reutilizáveis para futuras revisões

Os prompts abaixo podem ser adaptados para revisar renda fixa ou outros temas a partir de fontes selecionadas no NotebookLM.

### Resumo para revisão rápida

> Com base exclusivamente nas fontes deste notebook, crie um resumo de revisão sobre [tema]. Priorize os conceitos essenciais, utilize linguagem clara e evite repetições. Não acrescente informações externas às fontes.

### Comparação entre conceitos

> Com base exclusivamente nas fontes deste notebook, compare [conceito A] e [conceito B]. Organize a resposta considerando definição, funcionamento, principais diferenças e pontos importantes para revisão.

### Glossário

> Com base exclusivamente nas fontes deste notebook, crie um glossário com os principais conceitos relacionados a [tema]. Apresente cada termo seguido de uma definição curta e didática.

### Revisão por perguntas

> Com base exclusivamente nas fontes deste notebook, elabore 10 perguntas de revisão sobre [tema], variando entre questões conceituais e situações práticas. Apresente o gabarito apenas ao final.

### Identificação de pontos essenciais

> Analise exclusivamente as fontes deste notebook e selecione os 10 pontos mais importantes sobre [tema] que um iniciante deveria memorizar. Explique cada ponto de forma breve e objetiva.

## ✅ Conclusão

O desenvolvimento deste projeto permitiu experimentar o NotebookLM como ferramenta de aprendizagem ativa, utilizando fontes selecionadas previamente como base para estudo.

Os testes mostraram que a qualidade da resposta não depende apenas do tema perguntado, mas também da forma como o prompt define objetivo, estrutura, nível de detalhamento e limites da resposta.

A evolução entre os prompts demonstrou que instruções mais específicas permitem transformar um mesmo conjunto de fontes em materiais destinados a diferentes momentos do aprendizado, como estudo inicial, aprofundamento e revisão rápida.

Como resultado, foi produzido um miniguia introdutório sobre renda fixa, acompanhado de glossário e prompts reutilizáveis para futuras revisões.
