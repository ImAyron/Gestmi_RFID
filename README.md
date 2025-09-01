

# Sistema Integrado Gestmi com RFID
![GitHub repo size](https://img.shields.io/github/repo-size/ImAyron/Gestmi_RFID?style=for-the-badge )
![GitHub language count](https://img.shields.io/github/languages/count/ImAyron/Gestmi_RFID?style=for-the-badge )
![GitHub forks](https://img.shields.io/github/forks/ImAyron/Gestmi_RFID?style=social )
![GitHub stars](https://img.shields.io/github/stars/ImAyron/Gestmi_RFID?style=social )


Este repositório contém o código-fonte do **Sistema Integrado Gestmi**, uma solução de gerenciamento que utiliza uma antena RFID para leitura e rastreamento de objetos. O sistema foi desenvolvido com o framework Laravel e opera na faixa de frequência de 900 MHz.

## 📝 Descrição

O sistema Gestmi foi projetado para permitir a leitura e o gerenciamento de tags RFID em uma variedade de aplicações, desde controle de acesso até rastreamento de inventário. Utilizando a tecnologia RFID na faixa de frequência de 900 MHz, o sistema é capaz de identificar e rastrear objetos em tempo real, proporcionando uma solução robusta e eficiente para as necessidades da empresa Viaonda.

## 📡 O que é e como funciona o RFID?

RFID (Identificação por Radiofrequência) é uma tecnologia que usa ondas de rádio para identificar e rastrear objetos automaticamente, sem a necessidade de contato visual direto.

O processo pode ser resumido em 4 passos principais:

1.  **Ativação**: O leitor RFID emite um sinal de rádio de baixa potência, criando um campo eletromagnético.
2.  **Comunicação**: Quando uma tag RFID entra nesse campo, ela é energizada pelo sinal e envia de volta os dados armazenados em seu microchip.
3.  **Leitura e Processamento**: O leitor captura os dados da tag e os envia para o sistema de software (neste caso, o Gestmi).
4.  **Ação**: O sistema processa os dados e executa uma ação, como registrar um item no inventário, abrir uma porta ou exibir informações na tela.



## ✨ Recursos Principais

-   **Leitura de Tags RFID**: Capacidade de ler e interpretar dados de tags RFID na faixa de frequência de 900 MHz.
-   **Gerenciamento de Inventário**: Funcionalidade para gerenciar o inventário de forma eficiente, permitindo a identificação rápida e precisa de itens.
-   **Controle de Acesso**: Possibilidade de integração com sistemas de controle de acesso para permitir ou negar a entrada com base na identificação por RFID.
-   **API RESTful**: Interface de programação de aplicativos (API) RESTful para integração com outros sistemas e serviços.

## 🛠️ Tecnologias Utilizadas

-   **Backend**: [Laravel](https://laravel.com/) (Framework PHP)
-   **Linguagem**: [PHP](https://www.php.net/)
-   **Banco de Dados**: [SQLite](https://www.sqlite.org/index.html)
-   **Frontend**: HTML, CSS, JavaScript

## 🚀 Instalação e Uso

Siga os passos abaixo para configurar o ambiente de desenvolvimento local.

1.  **Clone o repositório:**
    ```bash
    git clone https://github.com/seuusuario/IC-jet-admin.git
    cd IC-jet-admin
    ```

2.  **Instale as dependências do Composer:**
    ```bash
    composer install
    ```

3.  **Configure o ambiente:**
    Copie o arquivo `.env.example` para `.env` e configure as variáveis de ambiente, incluindo a conexão com o banco de dados.
    ```bash
    cp .env.example .env
    ```

4.  **Gere a chave do aplicativo:**
    ```bash
    php artisan key:generate
    ```

5.  **Execute as migrações do banco de dados:**
    Isso criará as tabelas necessárias para o sistema.
    ```bash
    php artisan migrate
    ```

6.  **Inicie o servidor de desenvolvimento:**
    ```bash
    php artisan serve
    ```

7.  **Acesse o sistema:**
    Abra seu navegador e acesse `http://localhost:8000`.

## 🤝 Contribuição

Contribuições são muito bem-vindas! Se você encontrar um bug, tiver uma sugestão de melhoria ou quiser adicionar um novo recurso, sinta-se à vontade para:

-   Abrir uma [Issue](https://github.com/seuusuario/IC-jet-admin/issues).
-   Enviar um [Pull Request](https://github.com/seuusuario/IC-jet-admin/pulls).

## 📄 Licença

Este projeto está licenciado sob a **MIT License**. Veja o arquivo [LICENSE](LICENSE) para mais detalhes.

---
Espero que este formato seja exatamente o que você precisava!

O que mais podemos fazer?
*   Posso ajudar a criar um diagrama de arquitetura para o sistema?
*   Gostaria de explorar as diferenças entre as faixas de frequência de RFID (LF, HF, UHF)?
*   Podemos pesquisar bibliotecas ou pacotes Laravel específicos para integração com hardware RFID?
