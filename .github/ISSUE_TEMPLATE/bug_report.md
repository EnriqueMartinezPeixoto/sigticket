---
name: 🐛 Relatório de Bug
about: Reportar um bug identificado no sistema legado
title: '[BUG] '
labels: bug
assignees: ''
---

## 📋 Descrição do Bug

Descreva de forma clara e objetiva qual é o problema.

**Exemplo:** "A função `mudar_status()` aceita qualquer string como status, permitindo valores inválidos como 'xpto' ou '123'."

---

## 🔍 Como Reproduzir

Passos para reproduzir o comportamento:

1. Execute '...'
2. Entre com o valor '....'
3. Observe o erro '....'

---

## ✅ Comportamento Esperado

Descreva o que DEVERIA acontecer.

**Exemplo:** "O sistema deveria aceitar apenas os status: 'aberto', 'em_andamento', 'resolvido', 'fechado'."

---

## ❌ Comportamento Atual

Descreva o que ESTÁ acontecendo (errado).

**Exemplo:** "O sistema aceita qualquer string, incluindo valores absurdos."

---

## 💡 Proposta de Solução

Como você sugere corrigir isso?

**Exemplo:** 
status_validos = ["aberto", "em_andamento", "resolvido", "fechado"]
if novo_status not in status_validos:
print("Status inválido!")
return False

---

## 📊 Prioridade

- [ ] 🔴 Alta (sistema quebra ou segurança)
- [ ] 🟡 Média (funcionalidade incorreta)
- [ ] 🟢 Baixa (melhoria ou cosmético)

---

## 🏷️ Classificação

- [ ] `bug` - Comportamento incorreto
- [ ] `security` - Problema de segurança
- [ ] `data-validation` - Validação de dados
- [ ] `logic-error` - Erro de lógica
