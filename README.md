### FinAPI - Financeira

---

### Requisitos

- [ok] Deve ser possível criar uma conta
- [ok] Deve ser possível buscar o extrato bancário do cliente
- [ok] Deve ser possível realizar um depósito
- [ok] Deve ser possível realizar um saque
- [ok] Deve ser possível buscar o extrato bancário do cliente por data
- [ok] Deve ser possível atualizar dados do cliente
- [ok] Deve ser possível obter dados da conta do cliente
- [ok] Deve ser possível deletar uma conta
- [] Deve ser possível retornar o balance

---

### Regrás de negócio

- [ok] Não pode ser possível cadastrar uma conta com CPF já existente
- [ok] Não pode ser possível fazer depósito em uma conta não existente
- [ok] Não pode ser possível buscar extrato em uma conta não existente
- [ok] Não pode ser possível fazer saque em uma conta não existente
- [ok] Não pode ser possível excluir uma conta não existente
- [ok] Não pode ser possível fazer saque quando o saldo for insuficiente
