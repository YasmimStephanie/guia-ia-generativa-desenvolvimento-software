# 🤖 IA Generativa no Desenvolvimento de Software

Este projeto foi desenvolvido como parte de um desafio prático da DIO, com o objetivo de explorar a Inteligência Artificial Generativa como ferramenta de aprendizagem ativa e apoio ao desenvolvimento de software.
O estudo foi realizado utilizando o NotebookLM como ferramenta de organização e análise das fontes selecionadas, com foco em engenharia de prompts, geração de código, debugging, refatoração, testes e pensamento crítico.
O projeto apresenta experimentos práticos com diferentes estratégias de elaboração de prompts, documentando os resultados obtidos, as dificuldades encontradas e os ajustes realizados para melhorar a qualidade das respostas.

## 🎯 Contexto e Objetivos

### Contexto
A Inteligência Artificial Generativa vem transformando o desenvolvimento de software, sendo utilizada como ferramenta de apoio em atividades como geração e explicação de código, debugging, refatoração, criação de testes e documentação.
Apesar de contribuir para a produtividade dos programadores, seu uso exige conhecimento técnico e pensamento crítico, pois as respostas geradas podem apresentar erros, informações imprecisas ou soluções inadequadas. Nesse contexto, a Engenharia de Prompts se torna uma habilidade importante para orientar a IA de maneira mais eficiente, fornecendo contexto, instruções e critérios claros.
Este projeto tem como objetivo explorar, por meio do NotebookLM, o uso estratégico da Inteligência Artificial Generativa no desenvolvimento de software. Serão realizados experimentos com diferentes técnicas de elaboração de prompts, analisando os resultados obtidos, as dificuldades encontradas e as melhorias realizadas ao longo do processo.

### Objetivo Geral

Criar um guia prático para programadores de nível intermediário sobre o uso estratégico da Inteligência Artificial Generativa no desenvolvimento de software, com foco em Engenharia de Prompts e aplicações práticas.

### Objetivos Específicos
Compreender os fundamentos da IA Generativa e da Engenharia de Prompts;
Explorar técnicas de criação e aprimoramento de prompts;
Investigar aplicações da IA em geração de código, debugging, refatoração e testes;
Analisar limitações e riscos do código gerado por IA;
Desenvolver estratégias para revisar e validar respostas produzidas pela IA;
Documentar experimentos, resultados e dificuldades encontradas;
Criar uma coleção de prompts reutilizáveis para apoiar atividades de programação;
Consolidar os conhecimentos em um miniguia prático para uso consciente e estratégico da IA.

## 🧠 Uso do NotebookLM

O NotebookLM foi utilizado como ferramenta de aprendizagem ativa e organização do conhecimento.

As fontes selecionadas foram adicionadas ao notebook e utilizadas para:

- Realizar perguntas sobre os conteúdos;
- Comparar informações entre diferentes fontes;
- Identificar conceitos recorrentes;
- Criar resumos;
- Explorar aplicações práticas;
- Elaborar perguntas estratégicas;
- Validar informações por meio das referências apresentadas.

## 🧠 Caderno Temático no NotebookLM

O NotebookLM foi utilizado como ferramenta de aprendizagem ativa para explorar os conteúdos, realizar perguntas estratégicas, comparar informações entre as fontes e apoiar a organização dos conhecimentos relacionados ao uso da Inteligência Artificial Generativa no desenvolvimento de software.

🔗 **Acesse o Caderno Temático no NotebookLM:** [https://notebooklm.google.com/notebook/30d0e86e-1c8f-4260-942f-7741cd6740f0]


| Experimento           | Problema inicial         | Melhoria aplicada        | Resultado                 |
| --------------------- | ------------------------ | ------------------------ | ------------------------- |
| Engenharia de Prompts | Resposta genérica        | Adição de contexto       | Resposta mais direcionada |
| Geração de Código     | Requisitos insuficientes | Restrições               | Código mais adequado      |
| Debugging             | Falta de contexto        | Informações sobre o erro | Análise mais detalhada    |
| Refatoração           | Critérios subjetivos     | Critérios definidos      | Melhor controle           |
| Testes                | Pouca cobertura          | Casos específicos        | Mais cenários             |


# 📖 Miniguia Prático: IA Generativa para Programadores

Este miniguia apresenta estratégias práticas para utilizar a Inteligência Artificial Generativa como ferramenta de apoio ao desenvolvimento de software. O objetivo não é substituir o conhecimento técnico do programador, mas utilizá-la para auxiliar em tarefas como geração de código, debugging, refatoração, testes e documentação.

---

## 1. 🧠 Engenharia de Prompts

A Engenharia de Prompts consiste na criação de instruções claras e estruturadas para obter respostas mais precisas da IA.

Um bom prompt deve conter:

* Contexto do problema
* Objetivo da tarefa
* Instruções claras do que deve ser feito
* Restrições técnicas (linguagem, bibliotecas, etc.)
* Formato esperado da resposta
* Critérios de qualidade

### Exemplo

Prompt simples:

> Crie uma função para validar e-mail.

Prompt estruturado:

> Atue como um desenvolvedor JavaScript experiente. Crie uma função `validateEmail` que valide e-mails sem usar bibliotecas externas. Explique o código e forneça exemplos de uso com casos válidos e inválidos.

### 💡 Dica

Quanto mais contexto, melhor a resposta.

---

## 2. 💻 Geração de Código

A IA pode gerar código inicial para acelerar o desenvolvimento, mas sempre deve ser validado.

### Boas práticas ao pedir código:

* Linguagem e versão
* Objetivo da função
* Regras de negócio
* Restrições técnicas
* Formato de saída

### Exemplo

> Crie uma função em JavaScript que receba um array de produtos e retorne o valor total da soma dos preços. Trate lista vazia e não use bibliotecas externas.

### ⚠️ Importante

Sempre:

1. Entenda o código
2. Teste a execução
3. Valide requisitos
4. Verifique casos extremos
5. Revise segurança e performance

---

## 3. 🐛 Debugging com IA

A IA pode ajudar a identificar erros analisando código e comportamento inesperado.

### Inclua no prompt:

* Código completo
* Mensagem de erro
* Resultado esperado
* Resultado atual
* Ambiente de execução

### Exemplo

> Analise este código que retorna NaN. Explique possíveis causas, ordene as hipóteses por probabilidade e sugira testes para confirmar cada uma antes de corrigir.

### 💡 Dica

Peça análise, não apenas correção.

---

## 4. ♻️ Refatoração de Código

A IA pode ajudar a melhorar legibilidade, organização e manutenção do código.

### Critérios comuns:

* Legibilidade
* Reutilização
* Performance
* Boas práticas
* Segurança

### Exemplo

> Refatore o código abaixo mantendo o comportamento original. Explique cada melhoria e o motivo da alteração.

### 🔎 Fluxo ideal

Analisar → Identificar problemas → Refatorar → Comparar → Testar

---

## 5. 🧪 Testes de Software

A IA pode sugerir cenários de teste e casos extremos.

### Tipos de testes:

* Casos válidos
* Casos inválidos
* Valores nulos
* Entradas vazias
* Tipos incorretos
* Casos extremos

### Exemplo

> Crie uma estratégia de testes para esta função, incluindo casos de sucesso, erro e borda. Para cada caso, informe entrada e saída esperada.

### ⚠️ Importante

Sempre valide se os testes realmente cobrem os requisitos.

---

## 6. 📝 Documentação

A IA pode gerar documentação técnica de forma rápida e estruturada.

### Pode incluir:

* README
* Comentários de código
* Documentação de funções
* Exemplos de uso
* APIs

### Exemplo

> Gere documentação técnica para esta função explicando objetivo, parâmetros, retorno, exceções e exemplos.

### 💡 Dica

Sempre revise a documentação gerada.

---

## 7. 🔐 Limitações e Riscos

A IA não é perfeita e pode gerar erros.

### Principais riscos:

* Alucinações (informações falsas)
* Código incorreto
* Falhas de segurança
* Dependências inválidas
* Falta de contexto
* Exposição de dados sensíveis
* Dependência excessiva

---

## 8. ✅ Checklist de Uso

Antes de usar qualquer código gerado por IA:

* [ ] Entendi o código
* [ ] Testei a execução
* [ ] Validei requisitos
* [ ] Verifiquei casos extremos
* [ ] Analisei segurança
* [ ] Confirmei dependências
* [ ] Revisei boas práticas
* [ ] Não expus dados sensíveis

---

## 9. 🚀 Fluxo Recomendado

1. Entender o problema
2. Definir requisitos
3. Criar prompt claro
4. Analisar resposta da IA
5. Revisar solução
6. Testar
7. Refatorar se necessário
8. Documentar
9. Validar antes de produção

---

## 🎯 Conclusão

A IA Generativa é uma ferramenta poderosa para programadores, mas deve ser usada com pensamento crítico.

O melhor resultado acontece quando você combina:

**Conhecimento técnico + bons prompts + validação humana**


# 🏁 Conclusão do projeto 

O desenvolvimento deste projeto permitiu compreender que a Inteligência Artificial Generativa pode atuar como uma ferramenta de apoio durante diferentes etapas do desenvolvimento de software.

Os experimentos realizados demonstraram que a qualidade das respostas está diretamente relacionada à capacidade de fornecer contexto, definir objetivos e estabelecer critérios claros.

Entretanto, o uso de IA não elimina a necessidade de conhecimento técnico e pensamento crítico. O programador continua responsável por analisar, testar, validar e compreender o código produzido.

Dessa forma, a IA deve ser utilizada como uma ferramenta de apoio à produtividade e aprendizagem, e não como substituta da capacidade técnica do profissional.

