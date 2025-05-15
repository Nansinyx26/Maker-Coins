# Maker Coin System

## Sobre o Projeto

O **Maker Coin System** é um sistema simples baseado em **HTML, CSS e JavaScript** que permite gerenciar e visualizar pontos ("coins") atribuídos a alunos, organizados por turmas. Foi desenvolvido com foco em promover a **gamificação da aprendizagem** no ambiente escolar, tornando o acompanhamento de recompensas mais envolvente e intuitivo.

---

## Funcionalidades

- ✅ **Atualização de Coins**  
  Página dedicada para adicionar ou subtrair coins de alunos. Os valores são somados ao total existente, evitando duplicações e permitindo controle contínuo.

- ✅ **Padronização de nomes**  
  Os nomes dos alunos são normalizados (sem acentos, espaços extras ou variações de maiúsculas/minúsculas), evitando duplicidade e garantindo consistência.

- ✅ **Leaderboard por turma**  
  Exibe o ranking atualizado dos alunos e suas respectivas coins, separados por turmas (5°A, 5°B, 5°C).

- ✅ **Contador no topo da tela**  
  Exibe em tempo real o número total de alunos e a soma de coins da turma selecionada.

- ✅ **Exportação de dados**  
  Botão para exportar os dados da turma atual em `.txt`.

- ✅ **Histórico de atualizações**  
  Toda alteração feita em um aluno é registrada com data, hora e valor. O histórico pode ser consultado individualmente.

- ✅ **Barra de pesquisa por aluno**  
  Permite buscar o nome de um aluno e visualizar todo o seu histórico de atualizações.

- ✅ **Exclusão de aluno**  
  Remove os dados do aluno e também o seu histórico de alterações.

---

## Estrutura do Projeto

- `index.html` — Página inicial do sistema
- `atualizacao.html` — Página para cadastrar e atualizar coins dos alunos
- `frontend.html` — Página de leaderboard com visualização dos rankings por turma
- `style.css` — Estilização principal (layout, cores, botões, responsividade)
- `README.md` — Este documento explicativo sobre o projeto

---

## Como Usar

1. Abrir o arquivo `index.html` ou `atualizacao.html`.
2. Selecionar a turma (5°A, 5°B ou 5°C).
3. Preencher o nome do aluno e a quantidade de coins (positivo ou negativo).
4. Salvar os dados.
5. Usar o botão "Ver Leaderboard" para visualizar a classificação.
6. Utilizar o campo de pesquisa para consultar o histórico de qualquer aluno.

---

## Tecnologias Utilizadas

- HTML5  
- CSS3  
- JavaScript (com `localStorage` para armazenamento local)


