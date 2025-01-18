# Logbook

Este é um projeto de um diário pessoal desenvolvido com Django. Ele permite que os usuários criem, visualizem, editem e excluam entradas de diário.

## Funcionalidades

- **Listar Entradas**: Visualize todas as entradas do diário.
- **Detalhes da Entrada**: Veja os detalhes de uma entrada específica.
- **Criar Entrada**: Adicione uma nova entrada ao diário.
- **Editar Entrada**: Edite uma entrada existente.
- **Excluir Entrada**: Exclua uma entrada do diário.

## Instalação

1. Clone o repositório:
    ```sh
    git clone https://github.com/carvalhocaio/my-diary
    cd my-diary
    ```

2. Crie um ambiente virtual e ative-o:
    ```sh
    python -m venv venv
    source venv/bin/activate  # No Windows use `venv\Scripts\activate`
    ```

3. Instale as dependências:
    ```sh
    pip install -r requirements.txt
    ```

4. Execute as migrações do banco de dados:
    ```sh
    python manage.py migrate
    ```

5. Inicie o servidor de desenvolvimento:
    ```sh
    python manage.py runserver
    ```

6. Acesse o projeto no navegador:
    ```
    http://127.0.0.1:8000/
    ```

---
