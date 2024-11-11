# Projeto de Gestão de Liga de eSports

## Descrição

Este projeto tem como objetivo desenvolver um programa para a gestão de uma liga de desportos eletrónicos (eSports). A liga organiza torneios entre equipas, permitindo a criação e acompanhamento de partidas, equipas e jogadores. O sistema é projetado para suportar diferentes tipos de jogadores, como Jogadores de FPS, MOBA e eFootball.

## Funcionalidades

### Entidades Principais

1. **Jogador**
   - ID do jogador (gerado automaticamente)
   - Nome completo
   - Nickname
   - Estatísticas básicas (número de partidas jogadas, vitórias, derrotas)

   Tipos de Jogadores:
   - **JogadorFPS**
     - Precisão (percentagem de tiros acertados)
     - Headshots (número de headshots feitos)
   - **JogadorMOBA**
     - Personagem principal
     - KDA (número de abates, mortes e assistências)
   - **JogadorEFootball**
     - Posição principal
     - Número de golos marcados/defendidos

2. **Equipa**
   - ID da equipa (gerado automaticamente)
   - Nome da equipa
   - Lista de jogadores
   - Número de vitórias e derrotas

3. **Treinador**
   - ID do treinador (gerado automaticamente)
   - Nome completo
   - Email
   - Equipa gerida

4. **Administrador**
   - ID do administrador (gerado automaticamente)
   - Nome completo
   - Email

5. **Torneio**
   - ID do torneio (gerado automaticamente)
   - Nome do torneio
   - Jogo (CS2, eFootball, LoL)
   - Equipas participantes
   - Lista de partidas
   - Tabela de classificação

6. **Partida**
   - ID da partida (gerado automaticamente)
   - Equipa A
   - Equipa B
   - Resultado final
   - Data da partida

### Funcionalidades Principais

- **Jogador**
  - Autenticar-se no sistema
  - Ver/editar os seus dados pessoais
  - Ver os torneios em que participa
  - Ver as suas estatísticas pessoais

- **Treinador**
  - Autenticar-se como treinador
  - Criar e gerir a equipa
  - Inscrever a equipa em torneios
  - Acompanhar as partidas e resultados

- **Administrador**
  - Autenticar-se como administrador
  - Gerir utilizadores (Jogador e Treinador)
  - Criar e gerir torneios
  - Agendar partidas
  - Registar resultados e atualizar classificações

## Tecnologias Utilizadas

- Linguagem de Programação: [JAVA]
- Persistência de Dados: [Serialização]

## Estrutura do Projeto

O projeto está dividido em duas partes:
- **Back-end**: Lógica de negócio e manipulação de dados.
- **Front-end**: Interface de interação com o utilizador.

## Requisitos

- [Inserir requisitos de sistema ou dependências necessárias]

## Como Executar

1. Clone o repositório:
   ```bash
   git clone [URL do repositório]
