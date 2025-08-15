# Atividade-1.5
Este repositório, explica como clonar e Configurar um projeto existente em Laravel.

**Passo a Passo**

**1. Crie a pasta do projeto:**

Você pode criar uma nova pasta ou usar uma já existente:

mkdir [seu nome]

cd [seu_nome]

**2. Clone o projeto do GitHub:**
   
git clone https://github.com/usuario/atividade_laravel.git

cd atividade_laravel

**3. Instale dependências:**

composer install

**4. Crie o arquivo .env:**

cp .env.example .env

**5.Configure o banco de dados:**

DB_CONNECTION=mysql

DB_HOST=127.0.0.1

DB_PORT=3306

DB_DATABASE=laravel

DB_USERNAME=root

DB_PASSWORD=senha


**6. Gere o banco de dados e tabelas:**

php artisan migrate

**7. Gere a chave de criptografia da aplicação:**

php artisan key:generate

**8. Instalar dependências do NPM e compilar assets:**

npm install && npm run dev

**9. Rodar o servidor Laravel:**

php artisan serve

**10. Acesse a aplicação no navegador:**

http://127.0.0.1:8000.

**Teste a aplicação**

Verifique se a aplicação está carregando corretamente.

Agora você pode explorar as funcionalidades do projeto Laravel.

