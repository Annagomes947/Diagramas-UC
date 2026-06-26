# Caso de Uso: UC08 - Manter Prontuário

**Objetivo:** Permitir cadastrar, consultar, alterar e atualizar prontuários clínicos.

**Requisitos:** RF0007

**Atores:** Médico Veterinário

**Condição de Entrada:** Animal previamente cadastrado.

---

### Fluxo Principal

1. O veterinário seleciona um animal.
2. O sistema exibe o prontuário.
3. O veterinário informa: Peso; Temperatura; Diagnóstico; Procedimentos realizados; Medicamentos prescritos; Vacinas aplicadas; Exames solicitados; Observações clínicas.
4. O veterinário salva as informações.
5. O sistema atualiza o prontuário.
   
---

### Fluxos Alternativos
#### A1 - Consultar Prontuário

1. O veterinário localiza um animal.
2. O sistema exibe todo o histórico clínico.

#### A2 - Atualizar Prontuário

1. O veterinário executa **[A1]**.
2. O sistema exibe os dados atuais.
3. O veterinário adiciona ou altera informações clínicas.
4. O sistema salva as alterações.

---

### Fluxos de Exceção:
#### E1 - Animal Não Encontrado

1. O sistema não localiza o animal.
2. O sistema informa o erro ao veterinário.
