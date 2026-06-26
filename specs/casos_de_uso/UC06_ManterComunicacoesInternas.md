# Caso de Uso: UC06 - Manter Comunicações Internas

**Objetivo:** Permitir cadastrar, consultar, alterar e excluir comunicações internas.

**Requisitos:** RF0005

**Atores:** Auxiliar Administrativo, Profissional do Almoxarifado

**Condição de Entrada:** Usuário autenticado.

---

### Fluxo Principal

1. O usuário acessa o módulo de comunicações.
2. O sistema exibe o formulário.
3. O usuário informa: Assunto; Destinatário; Mensagem; Prioridade; Data.
4. O sistema verifica se as informações para cadastro são válidas. **[E1]**
5. O usuário confirma o envio.
6. O sistema registra a comunicação.

---

### Fluxos Alternativos
#### A1 - Consultar Comunicação

1. O usuário acessa a lista de comunicações.
2. O sistema exibe os registros.
3. O usuário seleciona uma comunicação.
4.O sistema exibe os detalhes.

#### A2 - Alterar Comunicação

1. O usuário executa. **[A1]**
2. O sistema exibe os dados atuais.
3. O usuário altera as informações.
4. O sistema salva as alterações.

#### A3 - Excluir Comunicação

1. O usuário seleciona uma comunicação.
2. O sistema solicita confirmação.
3. O usuário confirma.
4. O sistema remove o registro.

---

### Fluxos de Exceção:
#### E1 - Validação de Campos

1. Todas as informações são obrigatórias.
