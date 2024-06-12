# Ezoom

Teste para vaga de desenvolvedor.


## Pré-requisitos

Antes de começar, verifique se você possui os seguintes requisitos:

- PHP instalado
- Composer instalado
- Servidor web (por exemplo, Apache, Nginx) configurado
- Banco de dados (por exemplo, MySQL) configurado## Instalação

Siga estas etapas para configurar e rodar o projeto localmente:

Clone o repositório:

   ```bash
    git clone https://github.com/MarcelloMonteiro/ezoom-api
   ```

Navegue até o diretório do projeto:

    cd ezoom-api
    

Instale as dependências do projeto:
    
    composer install

Copie o arquivo de ambiente:
    
    remova o ".exemple" de .env.example
    deixe apenas .env

Gere a chave de aplicativo:

    php artisan key:generate

Execute as migrações do banco de dados:

    php artisan migrate

Execute as seeds para preencher o banco de dados com dados de exemplo:

    php artisan db:seed


## Rodando localmente

Inicie o servidor local:
    
    php artisan serve
    
O aplicativo estará acessível em http://localhost:8000.

