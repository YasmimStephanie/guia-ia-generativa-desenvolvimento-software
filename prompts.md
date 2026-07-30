## 🧪 Engenharia de Prompts 

Foram realizados cinco experimentos com diferentes estratégias de elaboração de prompts.

O objetivo foi observar como a inclusão de contexto, restrições, exemplos e formatos de saída influencia a qualidade das respostas.


### Experimento 1 — Engenharia de Prompts

**Prompt inicial:**

O que é engenharia de prompts?

**Problema identificado:**

A pergunta era muito ampla e poderia produzir uma resposta genérica.

**Estratégia aplicada:**

Foi adicionado contexto sobre desenvolvimento de software e definido o público-alvo.

**Resultado:**

A resposta passou a apresentar informações mais relevantes para programadores.


### Experimento 2 — Geração de Código

Prompt inicial:

Crie uma função JavaScript para validar um e-mail.

Problema identificado:

O prompt não apresentava requisitos suficientes, resultando em uma solução genérica e sem especificar critérios de validação ou casos extremos.

Estratégia aplicada:

Foram adicionados contexto, requisitos, restrições e formato esperado para a resposta.

Resultado:

A resposta tornou-se mais direcionada ao problema, apresentando código, explicações e exemplos. Ainda assim, foi necessário revisar e testar a solução para verificar sua adequação.


### Experimento 3 — Debugging

Prompt inicial:

Encontre o erro nesse código e corrija.

Problema identificado:

A solicitação não apresentava informações suficientes sobre o comportamento esperado, o erro ocorrido ou o contexto da aplicação, podendo levar a IA a fazer suposições.

Estratégia aplicada:

Foram adicionados o contexto do projeto, o comportamento esperado, o comportamento observado e a solicitação de análise de possíveis causas antes da correção.

Resultado:

A IA passou a apresentar uma análise mais detalhada das possíveis causas do problema, permitindo compreender o erro antes de aplicar uma solução.


### Experimento 4 — Refatoração de Código

Prompt inicial:

Refatore este código.

Problema identificado:

O termo "refatorar" é amplo e pode gerar diferentes interpretações. A IA poderia realizar alterações que modificassem o comportamento original do código.

Estratégia aplicada:

Foram definidos critérios específicos, como legibilidade, manutenção e boas práticas, além da orientação para preservar a funcionalidade original.

Resultado:

A resposta apresentou uma refatoração mais alinhada aos objetivos definidos, acompanhada de explicações sobre as alterações e seus benefícios.


### Experimento 5 — Criação de Testes

Prompt inicial:

Crie testes para essa função.

Problema identificado:

O prompt não especificava quais cenários deveriam ser considerados, resultando em uma cobertura de testes limitada.

Estratégia aplicada:

Foram incluídas orientações para considerar casos de sucesso, erros, entradas vazias, valores nulos, tipos inesperados e casos extremos.

Resultado:

A resposta passou a apresentar uma estratégia de testes mais abrangente, com diferentes cenários e resultados esperados. A análise humana continuou sendo necessária para verificar se os testes atendiam aos requisitos reais do sistema.
