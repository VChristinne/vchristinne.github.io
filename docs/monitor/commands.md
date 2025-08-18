---
title: Comandos
parent: Monitor
nav_order: 1
---

# Comandos
{: .no_toc }

- TOC
{:toc}

## Formas de Usar
1. Escreva o comando no chat do Discord exatamente como mostrado.
2. Digite `/` e selecione o ícone do MentorBot na lista da esquerda.

---

## Definir

- Função: Visualize todos os comandos.
- Endpoint: `/definir`
- Resposta: Lista completa dos comandos disponíveis e suas descrições.

---

## Referencias

- Função: Acesse guias de referência para perguntas mais frequentes.
- Endpoint:
  - `/referencias` - Menu de seleção com todas as opções de referência
  - `/referencias [opção]` - Acesso direto a uma referência específica (ex: `/referencias turma`)
- Opções:
  - Qual é a minha turma? - `turma`
  - Como participar da Aula Ao-Vivo? - `ao vivo`
  - Como entro em contato com o suporte e/ou coordenador? - `contato`, `suporte`, `coordenador`
  - Como funciona a estrutura/grade do curso? - `manual`, `manual aluno`, `manual do aluno`
- Resposta: Lista organizada de perguntas com respostas pré-definidas.
- Demo: [Assistir vídeo](https://github.com/user-attachments/assets/7ba8b9b0-cf56-4fab-b432-ef837c32e84b)

---

## Resolvido

- Função: Marque perguntas como resolvidas.
- Endpoint:** `/resolvido [MessageID]`
- Resposta: Marca como resolvida pelo [MessageID]({% link docs/monitor/faq.md %}) e recebe as informações por DM.
- Demo:
  - [Video da duvida resolvida](https://github.com/user-attachments/assets/47dde7e6-a77f-40d0-8000-ecd5fca8748e)
  - [Video da DM](https://github.com/user-attachments/assets/0614055b-5e12-49de-aa7a-32d96d48f476)

---

## Verificar

- Função: Verifique o status de uma pergunta.
- Endpoint: `/verificar [MessageID]`
- Resposta: Mostra se a pergunta está resolvida ou não pelo [MessageID]({% link docs/monitor/faq.md %}).

---

## Notificar _(Em Breve)_

- Função: Configure alertas opcionais por DM para novas perguntas.
- Endpoint: `/notificar`
- Resposta: Receberá por DM as informações de quem enviou a pergunta, curso e canal.

---

## Não Resolvido _(Em Breve)_

- Função: Remova status de resolvido.
- Endpoint: `/naoresolvido`
- Resposta: O status de resolvido foi removido da pergunta.
