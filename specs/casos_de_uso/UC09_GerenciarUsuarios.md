# Caso de Uso: UC09 - Gerenciar Usuários

**Objetivo:** Permitir cadastrar, alterar, consultar e remover usuários.

**Requisitos:** RF0010

**Atores:** Administrador

**Condição de Entrada:** Usuário autenticado.

---

### Fluxo Principal

1. O administrador acessa o módulo.
2. O sistema exibe o formulário.
3. O administrador informa: Nome; CPF; E-mail; Login; Perfil de acesso; Situação.
4. O sistema valida os dados. **[E1]**
5. O administrador confirma.
6. O sistema salva os dados.
7. O sistema exibe uma mensagem de sucesso.

---

### Fluxos Alternativos
#### A1 - Consultar Usuário

1. O administrador acessa a lista de usuários cadastrados.
2. O sistema apresenta os registros encontrados.
3. O administrador seleciona um usuário específico.
4. O sistema exibe os detalhes do perfil e situação do usuário.

#### A2 - Alterar Usuário

1. O admnistrador executa **[A1]**
2. O sistema exibe os dados atuais do formulário.
3. O administrador altera as informações necessárias.
4. O sistema valida os novos dados.
5. O sistema salva as alterações realizadas.
6. O sistema exibe uma mensagem de sucesso.

#### A3 - Remover Usuário

1. O admnistrador executa **[A1]**.
2. O administrador solicita a exclusão do registro.
3. O sistema solicita a confirmação da operação.
4. O administrador confirma.
5. O sistema remove o cadastro do usuário.
6. O sistema exibe uma mensagem de sucesso.

---

### Fluxos de Exceção:
#### E1 - Validação De Campos

1. Todas as informações são obrigatórias.

#### E2 - CPF ou Login Já Cadastrado

1. O sistema identifica duplicidade de CPF ou de Login durante a validação.
2. O sistema exibe uma mensagem de erro informando que o dado já existe no sistema.
3. O administrador permanece na tela para corrigir os campos duplicados.
