# Caso de Uso: UC05 - Manter Atendimentos

**Objetivo:** Permitir registrar, consultar, alterar e excluir atendimentos realizados na clínica.

**Requisitos:** RF0004

**Atores:** Recepcionista / Atendente, Médico Veterinário

**Condição de Entrada:** Animal e tutor previamente cadastrados.

---

### Fluxo Principal

1. O usuário acessa o módulo de atendimentos.
2. O sistema exibe o formulário.
3. O usuário informa: Animal; Tutor; Data do atendimento; Médico Veterinário responsável; Queixa principal; Diagnóstico; Procedimentos realizados; Medicamentos prescritos; Observações.
4. O usuário confirma o registro.
5. O sistema valida os dados.
6. O sistema salva o atendimento.
7. O sistema exibe mensagem de sucesso.

---

### Fluxos Alternativos
#### A1 - Consultar Atendimento

1. O usuário acessa a lista de atendimentos.
2. O sistema apresenta os registros cadastrados.
3. O usuário seleciona um atendimento.
4. O sistema exibe os detalhes.

#### A2 - Alterar Atendimento

1. O usuário localiza um atendimento existente.
2. O sistema apresenta os dados cadastrados.
3. O usuário altera as informações necessárias.
4. O sistema atualiza o registro.
5. O sistema exibe mensagem de sucesso.

#### A3 - Excluir Atendimento

1. O usuário seleciona um atendimento.
2. O sistema solicita confirmação.
3. O usuário confirma a exclusão.
4. O sistema remove o registro.
5. O sistema exibe mensagem de sucesso.

---

### Fluxos de Exceção:
#### E1 - Animal Não Cadastrado

1. O sistema informa que o animal não está cadastrado.
2. O usuário realiza o cadastro do animal.

#### E2 - Tutor Não Cadastrado
1. O sistema informa que o tutor não está cadastrado.
2. O usuário realiza o cadastro do tutor.
