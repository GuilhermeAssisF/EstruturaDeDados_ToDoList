# Gerenciador de Tarefas com Lista Duplamente Encadeada

Este repositório contém o código-fonte de um **Gerenciador de Tarefas** implementado como parte da disciplina **Estrutura de Dados 1**. O projeto foi desenvolvido utilizando uma **Lista Duplamente Encadeada** para gerenciar as tarefas, permitindo operações como inserção, remoção, e ordenação das tarefas com base na prioridade.

## Funcionalidades

- **Adicionar Tarefa no Início**: Adiciona uma nova tarefa no início da lista.
- **Adicionar Tarefa no Fim**: Adiciona uma nova tarefa no fim da lista.
- **Adicionar Tarefa em um Índice Específico**: Insere uma nova tarefa em uma posição específica da lista.
- **Adicionar Tarefa Ordenada por Prioridade**: Insere uma nova tarefa na lista de forma que ela fique ordenada pela prioridade.
- **Remover Tarefa do Início**: Remove a tarefa no início da lista.
- **Remover Tarefa do Fim**: Remove a tarefa no fim da lista.
- **Reordenar Lista por Prioridade**: Reordena todas as tarefas da lista com base na prioridade.
- **Mostrar Primeira Tarefa**: Exibe a primeira tarefa da lista sem removê-la.
- **Mostrar Tarefa Mais Antiga**: Exibe a tarefa que está há mais tempo na lista.
- **Salvar e Carregar Lista**: Permite salvar a lista de tarefas no LocalStorage do navegador e carregá-la posteriormente.

## Estrutura do Projeto

O projeto está organizado em três arquivos principais:

1. **index.html**: Interface do usuário para o gerenciador de tarefas.
2. **LinkedList.js**: Implementação da lista duplamente encadeada e métodos relacionados à manipulação de tarefas.
3. **Script.js**: Funções JavaScript que interagem com a interface e utilizam a lista duplamente encadeada para realizar as operações necessárias.
