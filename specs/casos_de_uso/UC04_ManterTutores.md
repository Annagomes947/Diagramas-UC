# Caso de Uso: UC04 - Manter Tutores

**Objetivo:** Permitir cadastrar, consultar, alterar e excluir tutores.

**Requisitos:** RF0003

**Atores:** Recepcionista / Atendente

**Condição de Entrada:** Usuário autenticado.

---

### Fluxo Principal

1. O usuário acessa o módulo de tutores.
2. O sistema exibe o formulário.
3. O usuário informa: Nome completo; CPF; Telefone; E-mail; Endereço; Plano de saúde associado.
4. O usuário confirma o cadastro.
6. O sistema valida os dados.
7. O sistema registra o tutor.
8. O sistema registra o tutor.
9. O sistema exibe mensagem de sucesso.

---

### Fluxos Alternativos
#### A1 - Alterar Tutor

1. O usuário localiza o tutor.
2. O sistema exibe os dados atuais.
3. O usuário altera as informações.
4.O sistema salva as alterações.

#### A2 - Excluir Tutor

1. O usuário localiza o tutor.
2. Solicita exclusão.
3. O sistema solicita confirmação.
4. O usuário confirma.
5. O sistema remove o cadastro.

---

### Fluxos de Exceção:
#### E1 - CPF Já Cadastrado

1. O sistema identifica duplicidade.
2. O sistema exibe mensagem de erro.
