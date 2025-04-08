
# Automação de Cadastro de Produtos

Este projeto tem como objetivo automatizar o processo de cadastro de produtos em uma aplicação web, utilizando a biblioteca PyAutoGUI para realizar ações na interface do usuário, como clicar, digitar e navegar, e a biblioteca Pandas para manipular e ler dados de um arquivo CSV contendo informações dos produtos.


## Funcionalidades

- Abrir o navegador Google Chrome.
- Navegar até uma página de login e realizar o acesso com as credenciais fornecidas.
- Ler um arquivo CSV contendo informações dos produtos.
- Automatizar o cadastro de cada produto, preenchendo os campos do formulário de maneira automática.


## Requisitos

- Python 3.x
- Bibliotecas utilizadas:
- Pyautogui 
- Pandas
- Navegador Google Chrome
- Um arquivo CSV chamado  com os seguintes campos:
- Código
- Marca
- Tipo 
- Categoria
- preco_unitario
- custo
- Obs

## Como usar

1. Instalar Dependências: Certifique-se de que as bibliotecas necessárias estão instaladas. Você pode instalá-las executando:

pip install pyautogui pandas

2. Preparar o Arquivo CSV: Insira os dados dos produtos no arquivo , garantindo que as colunas necessárias estejam presentes.

3. Executar script:

Certifique-se de que o navegador Google Chrome está instalado.
Execute o script Python em um ambiente configurado, usando python automacao_cadastro.py

4. Aguardar a Automação: O script abrirá o navegador, acessará o site de login, preencherá as informações e cadastrará os produtos automaticamente.
## Contribuindo

Contribuições são sempre bem-vindas!

Sinta-se à vontade para abrir issues ou fazer pull requests.

