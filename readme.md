# Landing Page Senhor dos Anéis

## Table of Contents

- [About](#about)
- [Prerequisites](#prerequisites)
- [Usage](#usage)

## About <a name = "about"></a>

Projeto criado para curso Desenvolvedor Fullstack Python da EBAC.

## Prerequisites <a name = "prerequisites"></a>

What things you need to install the software and how to install them.

1. Install Node.js
    
    installs fnm (Fast Node Manager)
    ```
    winget install Schniz.fnm
    ```
    download and install Node.js
    ```
    fnm use --install-if-missing 20
    ```
    
    verifies the right Node.js version is in the environment
    ```
    node -v # should print `v20.15.0`
    ```
    
    verifies the right NPM version is in the environment
    ```
    npm -v # should print `10.7.0`
    ```

2. Instalar Sass: 
    ```
    npm install -g sass  
    ```

## Installing & Usage <a name = "usage"></a>

1. Rodar o comando para processar o CSS:
    ```
    sass assets/scss/style.scss ./css/style.css 
    ```