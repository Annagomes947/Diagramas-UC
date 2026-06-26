# Caso de Uso: UC07 - Manter PLanos de Saúde

**Objetivo:** Permitir cadastrar, consultar, alterar e excluir planos de saúde.

**Requisitos:** RF0006

**Atores:** Recepcionista / Atendente, Auxiliar Administrativo

**Condição de Entrada:** Usuário autenticado.

---

### Fluxo Principal

1. O usuário acessa o módulo de planos.
2. O sistema exibe o formulário.
3. O usuário informa: Nome do plano; Empresa responsável; Telefone; E-mail; Cobertura; Coparticipação; Observações.
4. O sistema verifica se as informações para cadastro são válidas. **[E1]**, **[E2]**
5. O usuário confirma o cadastro.
6. O sistema registra o plano.

---

### Fluxos Alternativos
#### A1 - Consultar Plano

1. O usuário acessa a lista de planos.
2. O sistema exibe os registros.
3. O usuário seleciona um plano.
4. O sistema apresenta os detalhes.

#### A2 - Alterar Plano

1. O usuário executa **[A1]**.
2. O sistema apresenta os dados atuais.
3. O usuário altera as informações.
4. O sistema salva as alterações.

#### A3 - Excluir Plano

1. O usuário seleciona um plano.
2. O sistema solicita confirmação.
3. O usuário confirma.
4. O sistema remove o plano.

---

### Fluxos de Exceção:
#### E1 - Validação De Campos

1. Todas as informações são obrigatórias.

#### E2 - Plano Já Cadastrado

1. O sistema identifica duplicidade.
2. O sistema exibe mensagem de erro.
