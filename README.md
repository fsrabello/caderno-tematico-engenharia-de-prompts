Projeto prático desenvolvido para o desafio da DIO sobre aprendizagem ativa com Inteligência Artificial e NotebookLM.

🎯 Contexto e objetivos

Este projeto tem como tema Engenharia de Prompts para IA Generativa. A proposta é estudar como a forma de escrever instruções influencia a qualidade das respostas produzidas por modelos de linguagem.

O caderno temático foi estruturado para transformar a IA em uma ferramenta de aprendizagem ativa, e não apenas em uma ferramenta de geração automática de respostas.

Objetivos de estudo

Compreender o que é engenharia de prompts;

Identificar os elementos de um prompt eficaz;

Entender a importância de contexto, restrições e formato de saída;

Comparar recomendações de diferentes fornecedores de IA;

Conhecer técnicas como zero-shot e few-shot prompting;

Entender o processo de refinamento iterativo;

Reconhecer limitações como alucinações e riscos de prompt injection;

Criar prompts reutilizáveis para revisão e aprendizagem futura.

📚 Curadoria de fontes

Foram selecionadas fontes oficiais e abertas, publicadas por organizações que desenvolvem ou documentam soluções de Inteligência Artificial.

1. OpenAI — Práticas recomendadas de engenharia de prompt para o ChatGPT

🔗 https://help.openai.com/pt-br/articles/10032626-melhores-praticas-de-engenharia-de-prompts-para-o-chatgpt

Por que esta fonte foi escolhida: apresenta de forma objetiva princípios como clareza, especificidade, contexto e refinamento iterativo.

2. Google AI for Developers — Estratégias de design de comandos

🔗 https://ai.google.dev/gemini-api/docs/prompting-strategies?hl=pt-BR

Por que esta fonte foi escolhida: apresenta boas práticas de estruturação de prompts, uso de delimitadores, definição de parâmetros e controle do formato da resposta.

3. Anthropic — Prompting best practices

🔗 https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/prompt-templates-and-variables

Por que esta fonte foi escolhida: reúne práticas de clareza, contexto, exemplos, estruturação e controle do formato das respostas.

4. Microsoft Learn — Criar prompts efetivos para ferramentas de IA generativa

🔗 https://learn.microsoft.com/pt-br/training/modules/create-prompts-for-generative-ai-training-tools/

Por que esta fonte foi escolhida: material educacional voltado a iniciantes que aborda os elementos de um prompt eficaz e formas de avaliar clareza e relevância.

5. AWS — Prompt engineering best practices to avoid prompt injection attacks

🔗 https://docs.aws.amazon.com/prescriptive-guidance/latest/llm-prompt-engineering-best-practices/best-practices.html

Por que esta fonte foi escolhida: acrescenta uma perspectiva de segurança, mostrando que prompts também precisam considerar ataques de prompt injection e mecanismos de proteção.

🧭 Metodologia de estudo

O estudo foi organizado em quatro etapas:

Curadoria: seleção de fontes oficiais e confiáveis;

Questionamento: criação de perguntas estratégicas sobre o tema;

Refinamento: comparação entre prompts simples e prompts mais estruturados;

Consolidação: produção de um miniguia, glossário e conjunto de prompts reutilizáveis.

O ciclo utilizado foi:

Pergunta → Resposta → Avaliação → Ajuste do prompt → Nova tentativa

🔬 Engenharia de Prompts e “Cicatrizes”

A ideia desta seção é registrar não apenas o prompt final, mas também como uma pergunta pode ser melhorada ao longo do processo.

Experimento 1 — Prompt genérico

Prompt V1

Explique engenharia de prompts.

Análise

Esse prompt é válido, mas muito aberto. Ele não define:

público-alvo;

profundidade;

formato da resposta;

fontes a utilizar;

exemplos esperados;

tamanho da explicação.

Aprendizado

Quanto menor a quantidade de contexto fornecida, maior a liberdade do modelo para decidir sozinho o que deve abordar. Isso pode gerar uma resposta correta, porém genérica.

Experimento 2 — Adicionando contexto e formato

Prompt V2

Explique engenharia de prompts para uma pessoa iniciante em Inteligência Artificial. Use linguagem simples. Apresente uma definição, cinco características de um bom prompt e um exemplo prático. Baseie a resposta somente nas fontes deste caderno.

Melhorias em relação à V1

Foram adicionados:

público-alvo;

nível de linguagem;

quantidade de tópicos;

formato;

exemplo prático;

restrição de fontes.

Resultado consolidado

Um bom prompt tende a indicar com clareza o que deve ser feito, fornecer o contexto necessário, definir restrições importantes e informar o formato esperado da resposta. Fontes como OpenAI, Google, Anthropic e Microsoft convergem na importância de clareza e especificidade.

Experimento 3 — Comparação entre fontes

Prompt V3

Com base exclusivamente nas fontes deste caderno, compare as recomendações para criação de bons prompts. Identifique pontos em comum, diferenças e possíveis divergências. Para cada conclusão, indique em qual fonte ela está fundamentada.

Objetivo

Esse prompt foi criado para ir além de um simples resumo e estimular:

comparação;

síntese;

rastreabilidade;

identificação de padrões;

análise de divergências.

Resultado consolidado

Os materiais apresentam forte convergência nos seguintes pontos:

Clareza e especificidade: instruções vagas aumentam a ambiguidade;

Contexto: informações relevantes ajudam o modelo a interpretar corretamente a tarefa;

Formato de saída: indicar como a resposta deve ser apresentada melhora a previsibilidade;

Exemplos: demonstrações podem ajudar o modelo a seguir um padrão;

Iteração: prompts devem ser testados e refinados;

Estrutura: delimitadores, títulos ou tags podem separar instrução, contexto e dados;

Segurança: em aplicações reais, o prompt também precisa considerar manipulações e prompt injection.

A principal diferença entre as fontes está no foco: materiais da OpenAI, Google, Anthropic e Microsoft enfatizam principalmente a qualidade da interação, enquanto o material da AWS acrescenta maior ênfase em segurança.

Experimento 4 — Aprendizagem ativa

Prompt V4

Crie um quiz com 10 perguntas sobre engenharia de prompts usando apenas as fontes deste caderno. Não mostre as respostas inicialmente. Depois que eu responder, avalie cada item, explique meus erros e indique a fonte usada na correção.

Objetivo

Transformar a IA em uma ferramenta de revisão, permitindo que o estudante tente responder antes de receber a solução.

Aprendizado

Prompts de estudo são mais úteis quando obrigam o estudante a recuperar a informação, comparar ideias e justificar respostas, em vez de apenas ler um resumo pronto.

🩹 Principais “cicatrizes” do processo

1. Prompt genérico gera resposta genérica

Uma pergunta ampla pode produzir uma resposta útil, mas deixa muitas decisões por conta do modelo.

2. Contexto reduz ambiguidade

Informar o objetivo, o público e a situação melhora a adequação da resposta.

3. O formato deve ser solicitado

Se o resultado precisa ser uma tabela, lista, resumo, roteiro ou comparação, isso deve aparecer explicitamente no prompt.

4. Pedir fontes melhora a verificabilidade

Solicitar referências torna mais fácil conferir de onde cada conclusão veio.

5. Refinamento é parte do trabalho

Engenharia de prompts não significa encontrar uma “frase mágica”, mas testar, observar e ajustar.

6. IA não substitui validação

Uma resposta bem escrita ainda pode conter erros. Por isso, fontes e conferência continuam sendo importantes.

📖 Miniguia de Estudo

1. O que é um prompt?

Um prompt é a entrada ou instrução fornecida a um modelo de IA para orientar a tarefa que ele deve executar.

Exemplos:

“Resuma este texto.”

“Explique recursão para um iniciante.”

“Compare duas abordagens e apresente o resultado em uma tabela.”

2. O que é Engenharia de Prompts?

Engenharia de prompts é o processo de projetar, testar e aprimorar instruções para obter respostas mais úteis, adequadas e consistentes de modelos de IA.

O foco não é escrever prompts complicados, e sim reduzir ambiguidades e comunicar com clareza o objetivo da tarefa.

3. Anatomia de um bom prompt

Uma estrutura reutilizável é:

Papel

Define a perspectiva ou função desejada quando isso for útil.

Exemplo:
“Você é um tutor de programação para iniciantes.”

Contexto

Explica a situação e fornece informações necessárias.

Exemplo:
“Estou começando a estudar Python e ainda não aprendi funções.”

Tarefa

Diz exatamente o que deve ser feito.

Exemplo:
“Explique o conceito de funções.”

Restrições

Define limites e critérios.

Exemplo:
“Evite conceitos avançados e use no máximo 300 palavras.”

Formato de saída

Define como a resposta deve ser organizada.

Exemplo:
“Apresente definição, exemplo comentado e três exercícios.”

Exemplo completo

Você é um tutor de programação para iniciantes. Estou começando a estudar Python e ainda não conheço funções. Explique o conceito usando linguagem simples. Apresente uma definição, um exemplo comentado e três exercícios progressivos. Evite conceitos avançados.

🧰 Técnicas importantes

Zero-shot prompting

A tarefa é solicitada sem fornecer exemplos.

Exemplo:

Classifique a frase a seguir como positiva, negativa ou neutra: “O produto chegou no prazo.”

Few-shot prompting

O modelo recebe alguns exemplos antes de executar a nova tarefa.

Exemplo:

Texto: “Gostei muito do produto.”
Sentimento: Positivo

Texto: “O atendimento foi péssimo.”
Sentimento: Negativo

Texto: “O produto chegou ontem.”
Sentimento: Neutro

Texto: “Compraria novamente.”
Sentimento:

Os exemplos deixam mais claro o padrão desejado.

Refinamento iterativo

Consiste em melhorar o prompt progressivamente.

Versão 1

Explique Machine Learning.

Versão 2

Explique Machine Learning para um iniciante.

Versão 3

Explique Machine Learning para um iniciante usando uma analogia, um exemplo prático e no máximo 300 palavras.

A cada versão, novas informações reduzem a ambiguidade.

Delimitadores e estrutura

Em prompts maiores, títulos, Markdown, aspas ou tags podem ajudar a separar:

instruções;

contexto;

documentos;

exemplos;

pergunta final.

Exemplo:

### CONTEXTO
Estou estudando segurança em IA.

### TAREFA
Resuma os principais riscos.

### FORMATO
Apresente uma tabela com risco, exemplo e mitigação.

Grounding

Grounding significa apoiar a resposta em um conjunto definido de informações ou fontes.

Exemplo:

Responda utilizando exclusivamente os documentos fornecidos. Se a informação não estiver presente, informe que não há evidência suficiente no material.

Essa abordagem ajuda a reduzir respostas sem sustentação.

Prompt Injection

Prompt injection é uma tentativa de inserir instruções maliciosas ou conflitantes para fazer um sistema de IA ignorar regras ou executar comportamentos não desejados.

Em aplicações reais, segurança não deve depender apenas de um prompt. São necessários mecanismos adicionais, como validações, controles de acesso e guardrails.

📕 Glossário

Conceito

Definição

Prompt

Instrução ou entrada fornecida a um modelo de IA.

LLM

Large Language Model, modelo treinado para compreender e gerar linguagem.

Engenharia de prompts

Processo de criar, testar e aprimorar instruções para modelos de IA.

Contexto

Informações fornecidas para ajudar o modelo a compreender a tarefa.

Zero-shot

Solicitação de uma tarefa sem fornecer exemplos prévios.

Few-shot

Técnica que fornece alguns exemplos antes da tarefa principal.

System Prompt

Instruções de nível de sistema usadas para orientar comportamento e regras gerais do assistente.

Alucinação

Informação incorreta ou não sustentada gerada por um modelo.

Prompt Injection

Tentativa de manipular o comportamento de um sistema por meio de instruções inseridas na entrada.

Grounding

Uso de fontes ou contexto definido para fundamentar uma resposta.

Guardrail

Controle ou mecanismo usado para restringir comportamentos indesejados.

Refinamento iterativo

Processo de testar, avaliar e modificar prompts sucessivamente.

Formato de saída

Estrutura esperada para a resposta, como tabela, lista ou JSON.

♻️ Prompts reutilizáveis

1. Prompt para resumo

Com base exclusivamente nas fontes deste caderno, produza um resumo estruturado sobre [TEMA]. Divida em conceitos fundamentais, exemplos, aplicações e limitações. Indique as fontes utilizadas em cada seção.

2. Prompt para comparação de fontes

Compare o que as fontes deste caderno dizem sobre [CONCEITO]. Identifique pontos em comum, diferenças e possíveis divergências. Apresente o resultado em tabela e indique as fontes.

3. Prompt para aprender como iniciante

Explique [CONCEITO] como se eu estivesse estudando o assunto pela primeira vez. Use linguagem simples, uma analogia e um exemplo prático. Baseie-se somente nas fontes disponíveis.

4. Prompt para revisão

Crie 10 perguntas de revisão sobre [TEMA]. Não apresente as respostas inicialmente. Depois que eu responder, avalie cada resposta, explique os erros e indique a fonte usada na correção.

5. Prompt para flashcards

Crie 15 flashcards sobre os conceitos mais importantes das fontes. Para cada flashcard, apresente uma pergunta curta e uma resposta objetiva.

6. Prompt para identificar lacunas

Analise as fontes e identifique cinco perguntas importantes sobre o tema que não podem ser respondidas adequadamente apenas com o material disponível. Explique quais informações adicionais seriam necessárias.

7. Prompt para verificar afirmações

Analise a afirmação abaixo utilizando exclusivamente as fontes disponíveis. Classifique-a como sustentada, parcialmente sustentada ou não sustentada e mostre quais fontes justificam a conclusão.

8. Prompt para criar plano de revisão

Organize os conceitos deste caderno em um plano de revisão de 7 dias. Em cada dia, indique tópicos, uma pergunta de recuperação ativa e um pequeno exercício.

💡 Principais aprendizados

O principal aprendizado deste projeto é que usar Inteligência Artificial para estudar não significa apenas pedir respostas prontas.

A IA pode ser usada de forma mais ativa para:

comparar informações;

testar conhecimento;

gerar perguntas;

identificar lacunas;

organizar conteúdos;

revisar conceitos;

localizar evidências;

confrontar diferentes fontes.

A qualidade do resultado depende da combinação entre boas fontes, boas perguntas e avaliação crítica das respostas.

🚀 Conclusão

Este projeto mostrou como ferramentas de IA podem apoiar um processo de aprendizagem mais estruturado.

A combinação entre curadoria de fontes, pensamento crítico, engenharia de prompts, comparação de respostas e revisão transforma documentos dispersos em um caderno temático reutilizável.

Além do conhecimento técnico sobre prompts, o projeto reforçou uma habilidade importante para qualquer profissional que trabalhe com IA: saber formular boas perguntas, verificar respostas e melhorar continuamente o processo de obtenção de informação.

🛠️ Ferramentas utilizadas

NotebookLM

GitHub

Markdown

Inteligência Artificial Generativa
