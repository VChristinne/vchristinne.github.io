---
title: FAQ
parent: Monitor
nav_order: 2
---

# FAQ
{: .no_toc }

1. TOC
{:toc}

## Comandos com ID de Mensagem

Alguns comandos, como `/resolvido` e `/verificar`, precisam do MessageID para funcionar.
Para copiar o ID, é necessário ativar o Modo Desenvolvedor no Discord:
  1. Abra as _Configurações_ (ícone de engrenagem).
  2. Vá até a aba _Avançado_.
  3. Ative a opção _Modo Desenvolvedor_.
  4. Agora, basta clicar com o botão direito na mensagem desejada e selecionar _Copiar ID_.

## Desativar Notificações do MentorBot

Se não quiser receber mensagens diretas (DMs), você pode:

- Bloquear ou silenciar:
  - Clique com o botão direito no perfil do bot e selecione a opção equivalente.

Lembre-se que isso limita a utilidade de alguns comandos, como o `/resolvido`.

## Coleta de Dados para Relatórios

O MentorBot possui funções internas para monitorar o uso dos comandos pelos monitores:

- `summary`: Contagem geral de cada comando utilizado para obter insights dos mais úteis.
- `report`: Contagem individual, armazenando o hash do UserID e comandos usados.

Esses dados são usados **apenas para gerar relatório de uso** na Atividade Extensionista.
**Nenhum nome de usuário é divulgado** - apenas números totais e quantidade de usuários.
