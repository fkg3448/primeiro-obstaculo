# Exercício de QA — Heurística do Primeiro Obstáculo

## Objetivo

Este projeto foi criado para praticar a **Heurística do Primeiro Obstáculo** (The First Hurdle Heuristic), proposta por Michael Bolton.

A ideia da heurística é identificar rapidamente se a funcionalidade mais básica e essencial do sistema está funcionando antes de investir tempo em testes mais complexos.

Neste exercício, existe um defeito proposital que impede o funcionamento correto do fluxo principal da aplicação.

---

## Cenário

A aplicação simula uma tela simples de cadastro de usuários.

O usuário deve informar:

- Nome de usuário
- E-mail
- Senha
- Confirmação de senha

Ao clicar em **Cadastrar**, o sistema deveria criar um novo usuário.

---

## Desafio

Seu papel é atuar como QA e explorar a aplicação.

Antes de criar uma lista extensa de testes, tente responder:

- Qual é a principal funcionalidade desta tela?
- O usuário consegue concluir a ação principal?
- Existe algum obstáculo que bloqueia outros testes?
- Vale a pena continuar testando após encontrar esse obstáculo?

---

## O que avaliar

Durante a exploração, registre:

### Observações

- O que você tentou fazer?
- O que aconteceu?
- O comportamento foi o esperado?

### Riscos

- Quais funcionalidades dependem do sucesso do cadastro?
- Quais cenários ficam impossibilitados de serem testados?

### Impacto

- Qual é o impacto do problema encontrado para o usuário?
- O sistema ainda entrega valor sem essa funcionalidade?

---

## Perguntas para discussão

Após a execução dos testes, reflita sobre as seguintes perguntas:

1. Qual foi o primeiro obstáculo encontrado?
2. Quanto tempo levou para identificá-lo?
3. Como você percebeu que havia um problema?
4. Quais evidências utilizou?
5. Quais testes deixaram de ser executados por causa desse obstáculo?
6. O que você faria em seguida como QA?

---

## Conceitos trabalhados

- Testes exploratórios
- Heurística do Primeiro Obstáculo
- Priorização de testes
- Análise de risco
- Investigação de defeitos
- Comunicação de problemas
- Pensamento crítico em QA

---

## Ferramentas úteis durante o exercício

Os participantes são incentivados a utilizar:

- DevTools do navegador
- Aba Console
- Aba Network
- Observação da interface
- Pensamento exploratório

---

## Referência

**The First Hurdle Heuristic**

Autor: Michael Bolton

Publicado em: 14 de maio de 2024

A heurística sugere que, ao iniciar a avaliação de um produto, devemos primeiro verificar se ele consegue realizar sua função mais básica e essencial. Caso essa função falhe, muitos outros testes podem perder valor ou até se tornar impossíveis de executar.

---

## Resultado esperado do exercício

Ao final da atividade, os participantes devem compreender:

> Encontrar rapidamente um problema crítico pode ser mais valioso do que executar dezenas de testes em funcionalidades que dependem dele.

Essa é a essência da Heurística do Primeiro Obstáculo.
