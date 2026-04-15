# 📰 Projeto IA — Prompt Template: Newsletter Interna de Novos Produtos

> **Desafio Criativo — Curso de Inteligência Artificial**
> Template de prompt reutilizável para geração de newsletters internas padronizadas sobre novos produtos e funcionalidades.

---

## 📌 Sobre o Projeto

Este repositório contém um **template de prompt** desenvolvido para que qualquer pessoa do time de Comunicação Interna consiga gerar newsletters semanais sobre novos produtos — sem depender de inspiração, apenas preenchendo campos estruturados.

### ✅ O que este template resolve

- Falta de padronização entre newsletters de diferentes áreas
- Informações essenciais que ficavam de fora (o "por quê", o "pra quem", o "como usar")
- Dependência de redatores experientes para cada edição
- Inconsistência de tom e estrutura ao longo das semanas

---

## 🧱 Estrutura da Newsletter Gerada

| Bloco | Tipo | Objetivo |
|---|---|---|
| 📅 Identificação | Obrigatório | Informar semana, data e tema geral |
| 👋 Abertura | Obrigatório | Contextualizar a semana e criar conexão com o leitor |
| 🚀 Novidades da semana | Obrigatório | Apresentar cada produto/feature de forma completa e escaneável |
| 🔵 Resumo executivo | Automático (IA) | Permitir leitura em menos de 10 segundos |
| ❓ FAQ rápido | Opcional | Antecipar dúvidas e acelerar a adoção |
| 🔚 Encerramento | Recomendado | Reforçar próximos passos e onde tirar dúvidas |

---

## 🤖 Prompt Template — Copie e use sempre que precisar

```
Você é um(a) especialista em Comunicação Interna de produtos digitais.
Seu objetivo é criar uma newsletter interna para divulgação de novos 
produtos/funcionalidades, com linguagem clara, escaneável e acionável.

🎯 Objetivo
Gerar uma newsletter pronta para publicar a partir dos dados fornecidos,
mantendo consistência semanal.

🔴 Regras
- Escreva para público interno (colaboradores), com tom claro, direto e 
  motivador (sem exagero de marketing).
- Explique siglas na primeira vez que aparecerem.
- Não invente informações: se algo estiver faltando, marque como 
  "⚠️ Informação pendente".
- Use títulos curtos e bullets quando fizer sentido.
- Use português do Brasil.

📋 Formato obrigatório de saída (copie exatamente esta estrutura)

# 📰 Newsletter Interna – Novidades de Produto (SEMANA/DATA)

## 👋 Abertura (2-3 linhas)
[Contextualize a semana e o tema geral]

## 🚀 Novidades da semana
Para cada item, use o padrão:

### ⭐ Nome do Produto/Feature
- **O que é:**
- **Por que isso importa:**
- **Pra quem é:**
- **Como acessar/usar:**
- **Status:** (lançado / beta / piloto / em rollout / etc.)
- **Links úteis:** (docs, demo, roadmap, página interna)
- **CTA interno:** (o que a pessoa deve fazer agora)

## 🔵 Resumo executivo (gerado automaticamente)
Com base nas novidades acima, gere 3 bullets de no máximo 15 palavras cada.
-
-
-

## ❓ FAQ rápido (opcional, até 5 perguntas)
- **Pergunta:** Resposta

## 🔚 Encerramento (1-2 linhas)
[Reforce próximos passos e onde tirar dúvidas]

---

⚠️ Após gerar, sinalize ao final:
"✅ Newsletter gerada. Campos pendentes: [liste ou escreva 'nenhum']"

---

✏️ Dados de entrada (preenchidos por quem está solicitando):

SEMANA/DATA: 
TEMA GERAL: 

NOVIDADE 1
Nome do Produto/Feature:
O que é:
Por que isso importa:
Pra quem é:
Como acessar/usar:
Status:
Links úteis:
CTA interno:

NOVIDADE 2 (repita se necessário)
Nome do Produto/Feature:
O que é:
Por que isso importa:
Pra quem é:
Como acessar/usar:
Status:
Links úteis:
CTA interno:

RESUMO EXECUTIVO
- Não preencha. A IA vai gerar automaticamente com base nas novidades.

FAQ RÁPIDO (opcional)
- Pergunta: Resposta

ENCERRAMENTO (opcional, mas recomendado)
- Texto de encerramento (1-2 linhas):

📌 Regras de preenchimento:
- Se faltar alguma informação, escreva "⚠️ Informação pendente".
- Mantenha cada campo curto e direto.
- Não use siglas sem explicar no campo "O que é".
- Escreva tudo em português do Brasil, tom simples e colaborativo.
```

---

## 📝 Exemplo Preenchido — Teste e entenda o uso

> Copie o bloco abaixo completo e execute em qualquer IA (ChatGPT, Claude, Gemini etc.)

```
Você é um(a) especialista em Comunicação Interna de produtos digitais.
Seu objetivo é criar uma newsletter interna para divulgação de novos 
produtos/funcionalidades, com linguagem clara, escaneável e acionável.

🎯 Objetivo
Gerar uma newsletter pronta para publicar a partir dos dados fornecidos,
mantendo consistência semanal.

🔴 Regras
- Escreva para público interno (colaboradores), com tom claro, direto e 
  motivador (sem exagero de marketing).
- Explique siglas na primeira vez que aparecerem.
- Não invente informações: se algo estiver faltando, marque como 
  "⚠️ Informação pendente".
- Use títulos curtos e bullets quando fizer sentido.
- Use português do Brasil.

📋 Formato obrigatório de saída (copie exatamente esta estrutura)

# 📰 Newsletter Interna – Novidades de Produto (SEMANA/DATA)

## 👋 Abertura (2-3 linhas)
[Contextualize a semana e o tema geral]

## 🚀 Novidades da semana
Para cada item, use o padrão:

### ⭐ Nome do Produto/Feature
- **O que é:**
- **Por que isso importa:**
- **Pra quem é:**
- **Como acessar/usar:**
- **Status:** (lançado / beta / piloto / em rollout / etc.)
- **Links úteis:** (docs, demo, roadmap, página interna)
- **CTA interno:** (o que a pessoa deve fazer agora)

## 🔵 Resumo executivo (gerado automaticamente)
Com base nas novidades acima, gere 3 bullets de no máximo 15 palavras cada.
-
-
-

## ❓ FAQ rápido (opcional, até 5 perguntas)
- **Pergunta:** Resposta

## 🔚 Encerramento (1-2 linhas)
[Reforce próximos passos e onde tirar dúvidas]

---

⚠️ Após gerar, sinalize ao final:
"✅ Newsletter gerada. Campos pendentes: [liste ou escreva 'nenhum']"

---

✏️ Dados de entrada (preenchidos por quem está solicitando):

SEMANA/DATA: 03 a 07 de março
TEMA GERAL: Melhorias para acelerar onboarding e adoção de produtos internos

NOVIDADE 1
Nome do Produto/Feature: Portal de Onboarding 2.0
O que é: Nova área centralizada com trilhas por função e checklists automatizados
Por que isso importa: Reduz dúvidas recorrentes e diminui tempo para produtividade inicial
Pra quem é: Novos colaboradores e gestores responsáveis por onboarding
Como acessar/usar: Acessar via Intranet > Pessoas > Onboarding
Status: Rollout (30% das áreas)
Links úteis: https://intranet/portal-onboarding | https://docs/onboarding2
CTA interno: Testem a trilha da sua área e enviem feedback no canal #onboarding-feedback

NOVIDADE 2
Nome do Produto/Feature: Catálogo de Produtos Internos
O que é: Página única com todos os produtos internos, donos e guias rápidos
Por que isso importa: Ajuda a encontrar ferramentas certas e evita retrabalho
Pra quem é: Todos os times
Como acessar/usar: Acessar via Intranet > Produtos
Status: Lançado
Links úteis: https://intranet/catalogo-produtos
CTA interno: Favoritar a página e sugerir produtos faltantes via formulário interno

NOVIDADE 3
Nome do Produto/Feature: Integração SSO no Painel de Vendas
O que é: Login único (SSO — Single Sign-On) para acessar o painel sem múltiplas senhas
Por que isso importa: Menos fricção e mais segurança no acesso diário
Pra quem é: Time comercial e CS (Customer Success)
Como acessar/usar: Acessar normalmente pelo link do painel; autenticação será automática
Status: Beta
Links úteis: ⚠️ Informação pendente
CTA interno: Quem estiver no beta, reportar bugs no canal #painel-vendas

RESUMO EXECUTIVO
- Não preencha. A IA vai gerar automaticamente com base nas novidades.

FAQ RÁPIDO (opcional)
- Pergunta: O Portal de Onboarding substitui o processo atual?
  Resposta: Não, ele complementa. As trilhas guiam o novo colaborador, mas o gestor continua responsável pelo acolhimento.

ENCERRAMENTO (opcional, mas recomendado)
- Texto: Dúvidas sobre qualquer novidade? Fale no canal #produtos-internos ou com o time de Comunicação Interna. Até a próxima semana! 🚀
```

---

## 🚀 Como usar este template

1. Copie o bloco **Prompt Template** acima
2. Preencha os **Dados de entrada** com as informações da semana
3. Cole o prompt completo em qualquer IA (ChatGPT, Claude, Gemini etc.)
4. Revise os campos sinalizados como `⚠️ Informação pendente`
5. Publique!

---
