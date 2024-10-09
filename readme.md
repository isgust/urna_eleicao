# Urna Eletrônica - Flask

Este é um projeto de uma urna eletrônica em Flask que utiliza uma API para exibir os candidatos a vereador e prefeito da cidade de São Luís. O usuário insere os números correspondentes aos candidatos na urna via uma página web.

## Funcionalidades

- Exibição dos candidatos a vereador e prefeito via API.
- Interface web para inserção dos números dos candidatos.
- Confirmação dos votos inseridos.

## Tecnologias

- **Flask** (Python)
- **HTML/CSS** para a interface web
- **API** para obter candidatos

## Como executar o projeto

1. Clone o repositório:

    ```bash
    git clone https://github.com/seu-usuario/urna-eletronica-flask.git
    cd urna-eletronica-flask
    ```

2. Crie um ambiente virtual e ative-o:

    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows use: venv\Scripts\activate
    ```

3. Instale as dependências:

    ```bash
    pip install -r requirements.txt
    ```

4. Execute o servidor:

    ```bash
    flask run
    ```

5. Acesse no navegador:

    ```
    http://127.0.0.1:5000
    ```

