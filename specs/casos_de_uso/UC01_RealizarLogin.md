# **Caso de uso:**  UC01 - Realizar login

**Objetivo:** Permitir que usuários autenticados acessem o sistema AgendaPet conforme seu perfil de acesso.

**Requisitos:** RF0009

**Atores:** Tutor, Recepcionista / Atendente, Médico Veterinário, Auxiliar Administrativo, Profissional do Almoxarifado, Administrador, Equipe de Faturamento

**Condição de Entrada:** Usuário cadastrado e ativo no sistema.

---

### Fluxo Principal

1. O usuário acessa a tela de login.
2. O sistema exibe os campos: Usuário; Senha.
3. O usuário informa suas credenciais.
4. O usuário seleciona a opção "Entrar".
5. O sistema valida os dados.
6. O sistema identifica o perfil do usuário.
7. O sistema libera o acesso às funcionalidades permitidas.

---

### Fluxos Alternativos
#### **A1 - Recuperação de Senha**

1. O usuário seleciona "Esqueci minha senha".
2. O sistema solicita o e-mail cadastrado.
3. O usuário informa o e-mail.
4. O sistema envia instruções para redefinição.

---

### Fluxos de Exceção
#### **E1 - Credenciais Inválidas**

1. O sistema identifica dados incorretos.
2. O sistema exibe mensagem de erro.
3. O usuário permanece na tela de login.
