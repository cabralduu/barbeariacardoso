<<<<<<< HEAD
# 💈 World Barber
=======
# 💈 Barbearia Cardoso
>>>>>>> e1591234bfc477d44c6b084a1224f732161c7ca9

Sistema web de agendamento online para barbearia. Permite que clientes agendem horários, consultem e cancelem agendamentos. O painel administrativo oferece controle completo da agenda, serviços, clientes e faturamento.

---

## ✨ Funcionalidades

- **Agendamento online** — cliente escolhe data, serviço e horário disponível
- **Consulta por telefone** — cliente busca e cancela seus próprios agendamentos
- **Painel Admin** — gerenciar agendamentos, serviços, clientes e carteira financeira
- **Bloqueio de horários** — admin bloqueia intervalos fixos ou por data específica
- **Expediente configurável** — admin define horário de abertura e fechamento
- **Carteira financeira** — controle de faturamento mensal com gráficos
- **Histórico de atendimentos** — registro de todos os serviços realizados

---

## 🛠 Tecnologias

| Camada | Tecnologia |
|--------|-----------|
| Backend | PHP 8 + PDO |
| Banco de dados | MySQL |
| Frontend | HTML + Tailwind CSS |
| Gráficos | Chart.js |
| Hospedagem | InfinityFree |

---

## 🚀 Como rodar localmente

### Pré-requisitos
- PHP 8+
- MySQL
- Servidor local (XAMPP, WAMP ou similar)

### Passos

```bash
# 1. Clone o repositório
<<<<<<< HEAD
git clone https://github.com/cabralduu/worldbarber.git
cd worldbarber

# 2. Configure o banco de dados
# Importe o arquivo world_barber.sql no seu MySQL
=======
git clone https://github.com/cabralduu/barbeariacardoso.git
cd barbeariacardoso

# 2. Configure o banco de dados
# Importe o arquivo barbeariacardoso.sql no seu MySQL
>>>>>>> e1591234bfc477d44c6b084a1224f732161c7ca9

# 3. Configure as credenciais
cp config.example.php config.php
# Edite o config.php com seus dados de acesso ao banco

# 4. Inicie o servidor local e acesse
<<<<<<< HEAD
# http://localhost/worldbarber
=======
# http://localhost/barbeariacardoso
>>>>>>> e1591234bfc477d44c6b084a1224f732161c7ca9
```

---

## ⚙️ Configuração

Copie o arquivo `config.example.php` para `config.php` e preencha com suas credenciais:

```php
$host = 'seu_host';
$db   = 'seu_banco';
$user = 'seu_usuario';
$pass = 'sua_senha';
```

> O arquivo `config.php` está no `.gitignore` e nunca será enviado ao GitHub.

---

## 📁 Estrutura do projeto

```
<<<<<<< HEAD
worldbarber/
=======
barbeariacardoso/
>>>>>>> e1591234bfc477d44c6b084a1224f732161c7ca9
├── index.php           # Página principal (agendamento)
├── admin_login.php     # Login do administrador
├── admin_panel.php     # Painel administrativo
├── actions.php         # Lógica de negócio e funções
├── db.php              # Conexão com banco de dados
├── config.php          # Credenciais (não versionado)
├── config.example.php  # Modelo de configuração
<<<<<<< HEAD
├── world_barber.sql    # Estrutura do banco de dados
=======
├── barbeariacardoso.sql    # Estrutura do banco de dados
>>>>>>> e1591234bfc477d44c6b084a1224f732161c7ca9
└── icon.png            # Ícone do sistema
```

---

## 🗄 Banco de dados

<<<<<<< HEAD
O arquivo `world_barber.sql` contém toda a estrutura necessária para criar as tabelas:
=======
O arquivo `barbeariacardoso.sql` contém toda a estrutura necessária para criar as tabelas:
>>>>>>> e1591234bfc477d44c6b084a1224f732161c7ca9

- `bookings` — agendamentos pendentes
- `received_bookings` — atendimentos realizados
- `services` — serviços oferecidos
- `clients` — cadastro de clientes
- `wallet` — faturamento mensal
- `blocked_intervals` — horários bloqueados
- `schedule` — horário de funcionamento
- `admins` — usuários administradores

---

## 🔐 Segurança

- Senhas de admin com hash bcrypt (`password_hash` / `password_verify`)
- Proteção CSRF no painel administrativo
- Prepared statements em todas as queries (proteção SQL injection)
- Credenciais do banco separadas do código versionado
<<<<<<< HEAD
"# worldbarber" 
=======
"# barbeariacardoso" 
>>>>>>> e1591234bfc477d44c6b084a1224f732161c7ca9
