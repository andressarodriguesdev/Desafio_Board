# Desafio Board 

Projeto backend desenvolvido em Java para o desafio Board da Digital GFT (DIO). Trata-se de uma aplicação console que permite gerenciar boards, colunas e cards via linha de comando, com persistência em banco MySQL usando JDBC.

---

## Tecnologias

- Java 17+
- JDBC (Java Database Connectivity)
- MySQL 8.0+
- Gradle
- Lombok
- Git

---

## Descrição do Projeto

O sistema permite criar e gerenciar múltiplos **Boards**, que possuem colunas configuráveis e cards que podem ser criados, movidos entre colunas, bloqueados, desbloqueados, cancelados e visualizados. Tudo controlado via menu interativo no console.

### Funcionalidades principais

- Criar, listar, selecionar e deletar boards
- Definir colunas padrão e colunas adicionais em cada board
- Criar cards associados a uma coluna inicial
- Mover cards para colunas seguintes
- Bloquear e desbloquear cards com motivo
- Cancelar cards (movendo para coluna cancelamento)
- Visualizar informações detalhadas de boards, colunas e cards

---




