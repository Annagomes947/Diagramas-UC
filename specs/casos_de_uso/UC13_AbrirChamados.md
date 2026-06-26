# Caso de Uso: UC14 - Abrir Chamados

**Objetivo:** Solicitar suporte técnico.

**Requisitos:** RF1003

**Atores:** Tutor

**Condição de Entrada:** Usuário Autenticado.

---

### Fluxo Principal

1. O tutor acessa a área de suporte.
2. O sistema exibe o formulário.
3. O tutor informa: Assunto; Categoria; Descrição; Anexos.
4. O sistema valida os dados [E1].
5. O sistema gera um protocolo.

---

### Fluxos de Exceção:
#### E1 - Validação De Campos

1. O sistema identifica campos vazios.
2. O sistema informa o erro alertando que todas as informações são obrigatórias.
