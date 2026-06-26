# Caso de Uso: UC02 - Agendar Consultas

**Objetivo:** Permitir o agendamento de consultas veterinárias.

**Requisitos:** RF0001

**Atores:** Recepcionista / Atendente

**Condição de Entrada:** Tutor e animal previamente cadastrados.

---

### Fluxo Principal

1. O recepcionista acessa o módulo de consultas.
2. O sistema exibe o formulário.
3. O recepcionista informa: Tutor; Animal; Data da consulta; Horário; Médico Veterinário responsável; Tipo de atendimento; Observações.
4. O recepcionista confirma o agendamento.
5. O sistema valida os dados.
6. O sistema registra a consulta.
7. O sistema apresenta mensagem de sucesso.

---

### Fluxos Alternativos
#### A1 - Alterar Consulta

1. O recepcionista localiza uma consulta cadastrada.
2. O sistema apresenta os dados atuais.
3. O recepcionista altera as informações.
4. O sistema salva as alterações.

#### A2 - Cancelar Consulta

1. O recepcionista localiza a consulta.
2. Solicita o cancelamento.
3. O sistema solicita confirmação.
4. O recepcionista confirma.
5. O sistema cancela a consulta.

---

### Fluxos de Exceção:
#### E1 - Horário Indisponível

1. O sistema identifica conflito de horário.
2. O sistema informa a indisponibilidade.
3. O recepcionista escolhe outro horário.
