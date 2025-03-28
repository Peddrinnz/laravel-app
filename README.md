# Trabalho de Github em Laravel

### Sobre

Esse é um projeto da matéria de Framework 2 do curso superior em Análise de Sistemas no Instituto Federal de Educação, Ciência e Tecnologia de Mato Grosso do Sul.

#### Objetivos

Criem as classes Professor e Aluno na model, com seus respectivos controladores (sem os métodos)
No arquivo README.md coloque as instruções para executar o projeto no computador
Deem um push no projeto contendo a criação do controlador e model de Coordenador (lembrando que os commits devem conter verbos no gerúndio)
Crie uma branch 'Teste' e, na pasta 'views', crie uma arquivo contendo uma página estilizada (pode utilizar um framework CSS)

## Iniciando

Para executar esse projeto siga as instruções abaixo:

1. **Clonar o repositório:**

    - Clone o repositório do projeto para o seu ambiente local:
        ```sh
        git clone https://github.com/Peddrinz/laravel-app
        ```
    - Navegue até o diretório do projeto:
        ```sh
        cd laravel-app
        ```

2. **Verificar PHP e Composer na máquina:**

    - Certifique-se de que o PHP (versão 8.0 ou superior) e o Composer estão instalados.
    - Você pode verificar a instalação do PHP com o comando:
        ```sh
        php -v
        ```
    - Você pode verificar a instalação do Composer com o comando:
        ```sh
        composer -v
        ```

3. **Em SO Windows, verificar se a virtualização e o WSL estão ativados:**

    - Certifique-se de que a virtualização está ativada na BIOS do seu computador.
    - Verifique se o WSL (Windows Subsystem for Linux) está instalado e ativado.
    - Você pode instalar o WSL com o comando:
        ```sh
        wsl --install
        ```

4. **Verificar Node.js ou Bun na máquina:**

    - Certifique-se de que o Node.js (versão 14 ou superior) ou o Bun estão instalados.
    - Você pode verificar a instalação do Node.js com o comando:
        ```sh
        node -v
        ```
    - Você pode verificar a instalação do Bun com o comando:
        ```sh
        bun -v
        ```

5. **Instalar dependências do projeto:**

    - Navegue até o diretório do projeto e instale as dependências do Composer:
        ```sh
        composer install
        ```
    - Instale as dependências do Node.js ou Bun:
        ```sh
        npm install
        ```
        ou
        ```sh
        bun install
        ```

6. **Configurar o ambiente:**

    - Copie o arquivo [.env.example](http://_vscodecontentref_/0) para [.env](http://_vscodecontentref_/1):
        ```sh
        cp .env.example .env
        ```
    - Gere a chave da aplicação Laravel:
        ```sh
        php artisan key:generate
        ```

9. **Iniciar o servidor de desenvolvimento:**
    - Inicie o servidor de desenvolvimento do Laravel:
        ```sh
        php artisan serve
        ```

Agora você deve ser capaz de acessar o projeto em seu navegador no endereço `http://localhost:8000`.
