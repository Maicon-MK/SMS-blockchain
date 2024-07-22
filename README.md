# Blockchain em Python

Este é um projeto simples de implementação de uma blockchain em Python utilizando Flask. A aplicação permite minerar novos blocos, visualizar a cadeia de blocos e verificar a validade da cadeia.

## Tecnologias Utilizadas

- Python
- Flask

## Como Instalar e Rodar o Projeto

1. Clone o repositório:
    ```bash
    [git clone (https://github.com/Maicon-MK/SMS-blockchain)
    cd Modulo 1 - Criar Blockchain
    ```

2. Crie um ambiente virtual e ative-o:
    ```bash
    python -m venv venv
    source venv/bin/activate # Para Linux/Mac
    venv\Scripts\activate # Para Windows
    ```

3. Instale as dependências:
    ```bash
    pip install Flask
    ```

4. Rode a aplicação:
    ```bash
    python app.py
    ```

5. A aplicação estará rodando em `http://127.0.0.1:5000`.

## Endpoints da API

### Minerar Bloco

- **URL:** `/mine_block`
- **Método:** `GET`
- **Descrição:** Este endpoint minera um novo bloco e o adiciona à blockchain.

**Exemplo de Requisição no Postman:**
GET http://127.0.0.1:5000/mine_block


### Obter Cadeia de Blocos

- **URL:** `/get_chain`
- **Método:** `GET`
- **Descrição:** Este endpoint retorna a cadeia completa de blocos.

**Exemplo de Requisição no Postman:**

GET http://127.0.0.1:5000/get_chain

### Verificar Validade da Cadeia

- **URL:** `/is_valid`
- **Método:** `GET`
- **Descrição:** Este endpoint verifica se a cadeia de blocos é válida.

**Exemplo de Requisição no Postman:**
GET http://127.0.0.1:5000/is_valid
