# Caso de Uso: UC15 - Sincronizar Dados em Nuvem

**Objetivo:** Sincronizar dados entre ambiente local e cloud.

**Requisitos:** RF1004

**Atores:** Sistema

**Condição de Entrada:** Acesso à Internet.

---

### Fluxo Principal

1. O sistema identifica alterações.
2. O sistema sincroniza: Animais; Tutores; Consultas; Atendimentos; Prontuários.
3. O sistema confirma a sincronização.


### Fluxos de Exceção:
#### E1 - Erro ao sincronizar com a Nuvem.

1. Os dados não são sincronizados.
2. O sistema aguarda uma nova tentativa.
