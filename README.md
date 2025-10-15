
# 🏗️ GeezThor - Sistema de Gestão de Projetos de Arquitetura

**Interface**
<img width="2559" height="939" alt="image" src="https://github.com/user-attachments/assets/bcf22fdb-3360-4ec8-9efd-d6e8cdc164ec" />
<img width="2554" height="935" alt="image" src="https://github.com/user-attachments/assets/3ee77a54-cdcd-4b05-b496-40b9a247b288" />
<img width="2557" height="937" alt="image" src="https://github.com/user-attachments/assets/a003cc95-0989-4921-9a82-0b71b22a22db" />
<img width="2559" height="928" alt="image" src="https://github.com/user-attachments/assets/af755e21-9fed-4c20-a940-ad0e4f632d74" />


Sistema de gerenciamento de projetos de arquitetura desenvolvido com **Yii2 Framework**, PHP e MySQL.

-----

## 📖 Sobre o Projeto

O GeezThor é um sistema web para otimizar o gerenciamento de projetos de arquitetura. Ele centraliza o cadastro de projetos, acompanhamento de status, upload de arquivos e colaboração por meio de um sistema de comentários.

### Principais Funcionalidades

  - **Gestão Completa:** Cadastre projetos com detalhes como cliente, valor, status (Em andamento, Concluído) e pendências.
  - **Gerenciador de Arquivos:** Faça upload e download de múltiplos arquivos (plantas, documentos) por projeto.
  - **Colaboração:** Sistema de comentários integrado para registrar discussões e histórico.
  - **Autenticação:** Controle de acesso com login seguro para usuários.

-----

## ✅ Requisitos Essenciais

  - **PHP** \>= 7.4
  - **Composer**
  - **MySQL** ou **MariaDB**
  - **Extensões PHP:** `pdo_mysql`, `mbstring`, `openssl`, `fileinfo`

-----

## 🚀 Instalação Rápida

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/joaozucchetti/ProgIII-GeezThor.git
    cd ProgIII-GeezThor
    ```
2.  **Instale as dependências:**
    ```bash
    composer install
    ```
3.  **Crie o banco de dados** (`geezthor`) e importe o arquivo `geezthor.sql`.
4.  **Configure a conexão** com o banco no arquivo `config/db.php`.
5.  **Defina uma chave de segurança** (`cookieValidationKey`) no arquivo `config/web.php`.
6.  **Crie o diretório de uploads:**
    ```bash
    mkdir web\uploads
    ```

-----

## 🎮 Como Usar

1.  **Inicie o servidor** a partir da raiz do projeto:

    ```bash
    php yii serve --port=8081
    ```

2.  **Acesse o sistema** em `http://localhost:8081`.

3.  **Login Padrão:**

      - **Usuário:** `admin`
      - **Senha:** `senhadoadmin`

-----

## 👥 Equipe e Licença

  - **Desenvolvedores:** João Vitor Machado Zucchetti, Ana Carla Londero.
  - **Repositório:** [joaozucchetti/ProgIII-GeezThor](https://github.com/joaozucchetti/ProgIII-GeezThor)
  - **Licença:** Este é um projeto acadêmico com uso livre para fins educacionais.
<p align="center">
    <a href="https://github.com/yiisoft" target="_blank">
        <img src="https://avatars0.githubusercontent.com/u/993323" height="100px">
    </a>
    <h1 align="center">Yii 2 Basic Project Template</h1>
    <br>
</p>

Yii 2 Basic Project Template is a skeleton [Yii 2](https://www.yiiframework.com/) application best for
rapidly creating small projects.

The template contains the basic features including user login/logout and a contact page.
It includes all commonly used configurations that would allow you to focus on adding new
features to your application.

[![Latest Stable Version](https://img.shields.io/packagist/v/yiisoft/yii2-app-basic.svg)](https://packagist.org/packages/yiisoft/yii2-app-basic)
[![Total Downloads](https://img.shields.io/packagist/dt/yiisoft/yii2-app-basic.svg)](https://packagist.org/packages/yiisoft/yii2-app-basic)
[![build](https://github.com/yiisoft/yii2-app-basic/workflows/build/badge.svg)](https://github.com/yiisoft/yii2-app-basic/actions?query=workflow%3Abuild)
=
