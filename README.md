# modelo-previsao

Este repositório contém um modelo de previsão simples usando Flask e scikit-learn.

## Passos para configurar o projeto

1. Clone o repositório:
    ```bash
    git clone https://github.com/seu-usuario/modelo-previsao.git
    cd modelo-previsao
    ```

2. Crie um ambiente virtual e ative-o:
    ```bash
    python -m venv venv
    source venv/bin/activate  # No Windows, use `venv\Scripts\activate`
    ```

3. Instale as dependências:
    ```bash
    pip install -r requirements.txt
    ```

4. Execute a aplicação:
    ```bash
    python app.py
    ```

## Pontos de Extremidade

### /predict
- **Método:** POST
- **Descrição:** Endpoint para fazer previsões
- **Entrada:**
    ```json
    {
        "input": [1, 2, 3, 4, 5]
    }
    ```
- **Saída:**
    ```json
    {
        "prediction": [1, 2, 3, 4, 5]
    }
    ```

## Arquivos
- `app.py`: Código principal da aplicação Flask.
- `endpoints.json`: Documentação dos pontos de extremidade.
