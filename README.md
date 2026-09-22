# 🎨 Miniguia de Estudos: As 10 Heurísticas de Usabilidade de Jakob Nielsen com NotebookLM

> **Projeto prático desenvolvido para o desafio de projeto da DIO (Digital Innovation One)**  
> **Tema:** UX/UI Design, Avaliação Heurística e Design de Interação baseado na metodologia do Nielsen Norman Group (NN/g).

---

## 🎯 Contexto e Objetivos

Este projeto explora o **NotebookLM** como um **"Segundo Cérebro" virtual especializado em Jakob Nielsen**. O objetivo foi consolidar o conhecimento sobre as 10 Heurísticas de Usabilidade para análise, auditoria e construção de interfaces digitais mais intuitivas e eficientes.

### Objetivos de Estudo:
1. Compreender profundamente o significado e a aplicação prática das 10 Heurísticas de Usabilidade de Nielsen.
2. Treinar o NotebookLM para atuar como um auditor de UX/UI com base nas metodologias oficiais do Nielsen Norman Group (NN/g).
3. Desenvolver prompts estratégicos para realizar diagnósticos heurísticos e propor melhorias em telas/fluxos digitais.
4. Organizar um repositório de conhecimento prático e reutilizável para futuras revisões e avaliações de usabilidade.

---

## 📑 Curadoria de Fontes

Para alimentar a base do NotebookLM ("Segundo Cérebro"), foram selecionados artigos e guias abertos focados nas metodologias de Jakob Nielsen e do NN/g:

| Fonte | Autor / Instituição | Tipo de Conteúdo | Link / Referência |
| :--- | :--- | :--- | :--- |
| **10 Usability Heuristics for User Interface Design** | Jakob Nielsen (NN/g) | Artigo Técnico / Guia Oficial | [Acessar NN/g](https://www.nngroup.com/articles/ten-usability-heuristics/) |
| **How to Conduct a Heuristic Evaluation** | Jakob Nielsen (NN/g) | Artigo de Metodologia | [Acessar NN/g](https://www.nngroup.com/articles/how-to-conduct-a-heuristic-evaluation/) |
| **Usability Metrics & Severity Ratings** | Nielsen Norman Group | Guia de Avaliação e Gravidade | [Acessar NN/g](https://www.nngroup.com/articles/how-to-rate-the-severity-of-usability-problems/) |

---

## 🧪 Engenharia de Prompts & "Cicatrizes" (Troubleshooting)

Nesta seção, documentei a evolução dos prompts utilizados no NotebookLM para simular a persona do "Segundo Cérebro de Jakob Nielsen".

### Teste 1: Definindo a Persona do "Segundo Cérebro de Nielsen"
* **Prompt V1 (Incompleto):** *"O que são as 10 heurísticas de Nielsen?"*
  * **Resultado:** A IA listou os conceitos básicos em formato genérico, sem focar na aplicação analítica de um especialista em UX.
* **Prompt V2 (Com Persona e Contexto):** *"Atue como o 'Segundo Cérebro' de Jakob Nielsen. Com base nas fontes fornecidas, explique como a 1ª heurística (Visibilidade do Status do Sistema) evita a ansiedade do usuário em um fluxo de checkout e dê 2 exemplos de boas práticas."*
  * **Resultado:** A IA utilizou o tom metodológico do NN/g, destacando o uso de barras de progresso e feedbacks visuais em tempo real no checkout.

### Teste 2: Diagnóstico e Escala de Gravidade
* **Prompt V1 (Superficial):** *"Como avaliar se um aplicativo tem erros de usabilidade?"*
  * **Resultado:** Dicas genéricas de UX sem vincular à metodologia oficial de avaliação heurística.
* **Prompt V2 (Com Restrição e Estrutura):** *"Com base nos materiais do NN/g carregados, monte uma tabela com os 4 níveis da Escala de Severidade de Erros de Usabilidade de Nielsen (0 a 4), contendo: 'Nível', 'Classificação', 'Descrição' e 'Ação Recomendada'."*
  * **Resultado:** A IA gerou a tabela precisa (de 0 = Não é um problema até 4 = Catástrofe de usabilidade), fundamental para auditorias reais.

### 💡 Lições Aprendidas ("Cicatrizes"):
* **Encaminhamento de Persona:** Indicar claramente ao NotebookLM para agir como um "Especialista em Avaliação Heurística do NN/g" alterou significativamente a profundidade analítica das respostas.
* **Exigência de Cenários Práticos:** Sem pedir exemplos reais (e-commerce, apps mobile), as explicações ficavam restritas ao conceito acadêmico.

---

## 📘 Miniguia de Estudo (Entrega Final)

### 1. Resumo Estruturado das 10 Heurísticas de Nielsen

1. **Visibilidade do status do sistema:** O sistema deve sempre manter o usuário informado sobre o que está acontecendo por meio de feedbacks apropriados no tempo certo (ex: carregando, progresso de envio).
2. **Correspondência entre o sistema e o mundo real:** O sistema deve falar a linguagem do usuário, usando palavras, frases e conceitos familiares, em vez de jargões técnicos.
3. **Controle e liberdade do usuário:** Oferecer "saídas de emergência" claras caso o usuário cometa um erro sem querer (ex: botões de desfazer/refazer, cancelar).
4. **Consistência e padrões:** Os usuários não devem ter que adivinhar se palavras ou ações diferentes significam a mesma coisa (siga convenções de mercado).
5. **Prevenção de erros:** Mais do que boas mensagens de erro, um bom design previne que o erro aconteça em primeiro lugar (ex: confirmações antes de excluir algo).
6. **Reconhecimento em vez de memorização:** Minimize a carga cognitiva do usuário tornando objetos, ações e opções visíveis. Ele não deve ter que lembrar de informações de uma tela para outra.
7. **Flexibilidade e eficiência de uso:** Atalhos para usuários experientes sem poluir a interface para iniciantes (ex: atalhos de teclado, personalização).
8. **Estética e design minimalista:** Interfaces não devem conter informações irrelevantes. Cada elemento extra compete com as informações prioritárias.
9. **Ajudar os usuários a reconhecer, diagnosticar e recuperar-se de erros:** Mensagens de erro devem ser em linguagem clara (sem códigos estéreis), indicar o problema exato e sugerir uma solução.
10. **Ajuda e documentação:** Embora seja melhor que o sistema funcione sem documentação, pode ser necessário oferecer ajuda fácil de buscar e focada nas tarefas do usuário.

---

### 2. Glossário de Conceitos Chave

* **Avaliação Heurística:** Método de inspeção de usabilidade no qual especialistas analisam uma interface comparando-a com princípios de design reconhecidos (heurísticas).
* **Carga Cognitiva:** A quantidade de esforço mental necessária para que o usuário processe as informações e execute uma tarefa na interface.
* **Affordance:** Propriedade de um objeto que indica intuitivamente como ele deve ser usado (ex: um botão com relevo sugere que pode ser clicado).
* **Escala de Severidade:** Gradação (de 0 a 4) usada para priorizar a correção de problemas de usabilidade com base em frequência, impacto e persistência.
* **Feedback Visual:** Resposta imediata do sistema à ação do usuário (ex: mudança de cor em um botão ao passar o mouse ou clicar).

---

### 3. Toolkit de Prompts Reutilizáveis (Para Avaliações Futuras)

Copie e utilize estes prompts no seu NotebookLM para auditar projetos ou tirar dúvidas de UX:

1. **Prompt de Auditoria de Tela:**
   > *"Atue como Jakob Nielsen. Vou descrever os elementos de uma tela de [Tipo de Tela, ex: Login/Cadastro]. Analise essa estrutura com base nas 10 Heurísticas e indique quais heurísticas podem estar sendo violadas e como corrigi-las."*

2. **Prompt de Classificação de Erro (Severidade):**
   > *"Com base na Escala de Severidade do NN/g, classifique o seguinte problema de usabilidade: '[Descreva o problema]'. Justifique a nota de 0 a 4 dada ao problema."*

3. **Prompt de Gerador de Checklist de UX:**
   > *"Gere um checklist com 5 itens práticos baseados na Heurística [Inserir Heurística, ex: Prevenção de Erros] para que um desenvolvedor valide antes de subir uma nova funcionalidade para produção."*

---

## 🛠️ Tecnologias Utilizadas

* [NotebookLM](https://notebooklm.google.com/) - Curadoria de fontes e simulação de Segundo Cérebro de UX
* [GitHub](https://github.com/) - Hospedagem e documentação do projeto
* [Markdown](https://www.markdownguide.org/) - Formatação do repositório
