# Copilot - Computer Scott

Repositório de prompts estruturados para configurar um copiloto técnico, e otimizado para um fluxo de trabalho em Linux.

## Identidade e Stack

O assistente (Computer Scott) atua de forma direta, limpa e sem redundâncias. A geração de código exige comentários linha a linha para fins didáticos e foca-se na eficiência operacional, sem a utilização de emojis para garantir a compatibilidade e foco técnico.

* **Sistema Operativo:** Linux Lubuntu 25.10
* **Stack Principal:** HTML5, CSS3, JavaScript (Vanilla), Node.js v22.22.2, Python, Shell Script
* **Ferramentas:** NPM v10.9.7, VS Code, Android Studio, Git,GitHub

## Modos de Operação

O repositório contém as instruções principais e também as variantes focadas em DevOps e Backend.

### Ask (Diagnóstico e Análise)
* **Objetivo:** Entender e diagnosticar sem alterar código.
* **Aplicação:** Leitura de logs de erro, explicação de funções e respostas rápidas.
* **Pasta:** [Padrão](prompts/prompt-ask.md) | [DevOps/Backend](prompts/prompt-Copiloto-DevOps-Backend-ASK.md)

### Edit (Transformação de Código)
* **Objetivo:** Pegar no que já existe e transformar.
* **Aplicação:** Refactoring, ajustes de lógica de negócio, otimização de performance e tratamento de erros.
* **Pasta:** [Padrão](prompts/prompt-edit.md) | [DevOps/Backend](prompts/prompt-Copiloto-DevOps-Backend-EDIT.md)

### Plan (Desenho e Planeamento)
* **Objetivo:** Estruturar a abordagem técnica antes da codificação.
* **Aplicação:** Definição de escopo, mapeamento de ficheiros afetados, riscos e passos incrementais.
* **Pasta:** [Padrão](prompts/prompt-plan.md) | [DevOps/Backend](prompts/prompt-Copiloto-DevOps-Backend-PLAN.md)

### Agent (Execução Integrada)
* **Objetivo:** Transformar requisitos em implementações completas.
* **Aplicação:** Ciclo Descobrir-Planear-Implementar-Verificar, focado em scripts e comandos de terminal prontos a executar.
* **Pasta:** [Padrão](prompts/prompt-agent.md) | [DevOps/Backend](prompts/prompt-Copiloto-DevOps-Backend-AGENT.md)

### Study (Aprendizagem Ativa)
* **Objetivo:** Compreender ferramentas e lógicas a fundo.
* **Aplicação:** Aprendizagem reversa, analogias diretas e exemplos práticos com foco no terminal (Lubuntu) e na indústria.
* **Pasta:** [Padrão](prompts/prompt-study.md) | [DevOps/Backend](prompts/prompt-Copiloto-DevOps-Backend-STUDY.md)

## Como Utilizar e Testar

1. Navegue até à pasta `prompts/` e selecione o modo que melhor se adapta à sua tarefa atual.
2. Copie todo o conteúdo do arquivo Markdown selecionado.
3. Cole o texto nas instruções de sistema (System Prompt) ou como primeira mensagem na sua interface de IA.
4. Forneça o contexto do seu problema (blocos de código, logs do terminal, requisitos) e inicie a interação. O assistente adotará imediatamente a identidade e as regras de formatação.
