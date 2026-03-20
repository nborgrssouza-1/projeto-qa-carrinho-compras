# 📋 Casos de Teste - Carrinho de Compras

## 🎯 Cenário
Validar o funcionamento do carrinho de compras e finalização de pedido.

---

### ✅ CT01 – Adicionar produto ao carrinho
**Passos:**
1. Acessar página do produto
2. Clicar em “Adicionar ao carrinho”

**Resultado esperado:**
Produto deve ser exibido no carrinho com quantidade 1.

---

### ✅ CT02 – Alterar quantidade do produto
**Passos:**
1. Adicionar produto ao carrinho
2. Alterar quantidade para 3

**Resultado esperado:**
Quantidade e valor total devem ser atualizados corretamente.

---

### ❌ CT03 – Finalizar compra sem preencher dados
**Passos:**
1. Adicionar produto ao carrinho
2. Clicar em “Finalizar compra” sem preencher dados

**Resultado esperado:**
Sistema deve exibir mensagem de campos obrigatórios.

---

### ❌ CT04 – Inserir cartão inválido
**Passos:**
1. Preencher dados válidos
2. Inserir cartão inválido
3. Finalizar compra

**Resultado esperado:**
Sistema deve exibir mensagem de erro no pagamento.

---

### ❌ CT05 – Campo e-mail inválido
**Passos:**
1. Inserir e-mail sem “@”
2. Tentar finalizar cadastro

**Resultado esperado:**
Sistema deve exibir mensagem “E-mail inválido”.

---

### ⚠️ CT06 – Clique múltiplo no botão finalizar
**Passos:**
1. Preencher dados corretamente
2. Clicar várias vezes rapidamente em “Finalizar compra”

**Resultado esperado:**
Sistema deve processar apenas um pedido.