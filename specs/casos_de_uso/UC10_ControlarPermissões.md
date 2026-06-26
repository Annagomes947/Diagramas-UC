# Caso de Uso: UC10 - Controlar Permissões

**Objetivo:** Definir permissões de acesso.

**Requisitos:** RF0011

**Atores:** Administrador

**Condição de Entrada:** Usuário autenticado.

---

### Fluxo Principal

1. O administrador seleciona um usuário.
2. O sistema exibe os perfis.
3. O administrador define: Perfil; Módulos permitidos; Operações permitidas.
4. O sistema valida os dados [E1].
5. O sistema salva as permissões.

---

### Fluxos de Exceção:
#### E1 - Validação De Campos

1. O sistema identifica campos vazios ou permissões não selecionadas.
2. O sistema alerta que todas as informações são obrigatórias.
