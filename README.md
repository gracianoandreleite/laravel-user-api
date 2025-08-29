# Laravel User API 🔐

Uma API simples desenvolvida com **Laravel** para gerenciamento de usuários.  
Fornece endpoints para **criar, listar, atualizar e excluir usuários**.

---

## Tecnologias
- [Laravel 9+](https://laravel.com/)
- [PHP](https://www.php.net/)
- [MySQL](https://www.mysql.com/)
- [Composer](https://getcomposer.org/)

---

## Let's instail 🚀:

Siga os passos abaixo para rodar o projeto localmente.

### 1️⃣ Clonar o repositório

```bash
git clone https://github.com/gracianoandreleite/laravel-user-api.git
cd laravel-user-api
```

### 2️⃣ Instalar dependências
composer install

### 3️⃣ Configurar o ambiente

Copie o arquivo `.env.example` e configure:

``` bash
cp .env.example .env
```

Edite o `.env` e configure a conexão com o MySQL:

``` env
DB_DATABASE=api_laravel
DB_USERNAME=root
DB_PASSWORD=
```

### 4️⃣ Gerar chave da aplicação

``` bash
php artisan key:generate
```

### 6️⃣ Rodar o servidor local e as migrations

``` bash
php artisan serve
```
``` bash
php artisan migrate
```

Inicie o servidor local:
php artisan serve

A API estará disponível em:
👉 http://127.0.0.1:8000

### Endpoints
* `GET /api/users` → Listar usuários
* `GET /api/users/{id}` → Detalhar usuário
* `PUT /api/users/{id}` → Atualizar usuário
* `DELETE /api/users/{id}` → Remover usuário

### Parâmetros
* `name` → Nome do usuário
* `email` → E-mail do usuário

------------------------------------------------------------------------

## Contribuição

Contribuições são bem-vindas!\
Faça um **fork**, crie uma branch, faça suas alterações e abra um **Pull
Request**.

------------------------------------------------------------------------

## Licença

Este projeto está sob a licença MIT. Consulte o arquivo
[LICENSE](LICENSE) para mais detalhes.
