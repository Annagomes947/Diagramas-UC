# Caso de Uso: UC03 - Manter Animais

**Objetivo:** Permitir cadastrar, consultar, alterar e excluir animais.

**Requisitos:** RF0002

**Atores:** Recepcionista / Atendente

**Condição de Entrada:** Usuário autenticado.

---

### Fluxo Principal

1. O usuário seleciona "Cadastrar Animal".
2. O sistema exibe o formulário.
3. O usuário informa: Nome do animal; Espécie; Raça; Sexo; Data de nascimento; Peso; Cor; Tutor responsável.
4. O usuário confirma a operação.
5. O sistema valida os dados.
6. O sistema registra o animal.
7. O sistema exibe mensagem de sucesso.

---

### Fluxos Alternativos
#### A1 - Alterar Animal

1. O usuário localiza o animal.
2. O sistema exibe os dados cadastrados.
3. O usuário altera as informações.
4. O sistema salva as alterações.

#### A2 - Excluir Animal

1. O usuário seleciona o animal.
2. O sistema solicita confirmação.
3. O usuário confirma.
4. O sistema remove o cadastro.

---

### Fluxos de Exceção:
#### E1 - Campos Obrigatórios Não Informados

1. O sistema identifica campos vazios.
2. O sistema informa o erro.
3. O usuário corrige os dados.
