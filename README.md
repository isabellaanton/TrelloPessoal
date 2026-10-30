# Meu quadro pessoal

Aplicação pessoal de organização feita com React, TypeScript e Vite.

## Executar

1. Instale Node.js (versão 20.19 ou superior).
2. Abra esta pasta no terminal.
3. Rode `npm install` e depois `npm run dev`.
4. Abra o endereço local indicado pelo Vite.

## Organização dos dados

- `src/data/initial-board.json` contém o quadro inicial e exemplos de tarefas e etiquetas.
- As alterações feitas na aplicação são armazenadas como JSON no `localStorage` do navegador.
- `src/types.ts` define a estrutura dos dados usados no TypeScript.

As cores do quadro e das etiquetas são configuráveis dentro da aplicação. É possível criar, editar e excluir etiquetas, associá-las a tarefas e filtrar o quadro por etiqueta. Os dados ficam apenas neste navegador; sincronização entre dispositivos pode ser adicionada depois com uma base de dados.
