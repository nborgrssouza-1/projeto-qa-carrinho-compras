# 🐞 Bug Report - Carrinho de Compras

---

## 🔴 Bug 01 – Duplicação de pedidos

**Descrição:**
Sistema gera pedidos duplicados ao clicar múltiplas vezes no botão "Finalizar Compra".

**Severidade:** Crítica  
**Prioridade:** Alta  

**Passos para reproduzir:**
1. Adicionar produto ao carrinho
2. Preencher dados corretamente
3. Clicar várias vezes rapidamente em “Finalizar Compra”

**Resultado esperado:**
Apenas um pedido deve ser gerado.

**Resultado obtido:**
Sistema gera múltiplos pedidos.

---

## 🟡 Bug 02 – Validação de e-mail incorreta

**Descrição:**
Sistema aceita e-mails inválidos sem “@”.

**Severidade:** Média  
**Prioridade:** Média  

**Passos para reproduzir:**
1. Inserir e-mail inválido (ex: testeemail.com)
2. Tentar continuar

**Resultado esperado:**
Sistema deve bloquear e exibir erro.

**Resultado obtido:**
Sistema aceita o e-mail.

---

## 🟢 Bug 03 – Layout desalinhado no botão

**Descrição:**
Botão “Finalizar Compra” está desalinhado em dispositivos mobile.

**Severidade:** Baixa  
**Prioridade:** Baixa  

**Passos para reproduzir:**
1. Acessar sistema pelo celular
2. Ir até carrinho

**Resultado esperado:**
Botão deve estar centralizado.

**Resultado obtido:**
Botão aparece desalinhado.