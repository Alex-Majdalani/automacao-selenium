# 🤖 Automação de Formulário com Selenium

Este projeto utiliza Python, Selenium e Pandas para automatizar o preenchimento de um formulário do Google com base em uma planilha `.csv` contendo informações de produtos. Conhecimentos admiridos durante curso da Hashtag Treinamentos (https://www.hashtagtreinamentos.com/)

---

## 📌 Objetivo

Facilitar o preenchimento em massa de formulários com dados estruturados, economizando tempo e evitando erros manuais.

---

## 📁 Estrutura do Projeto
📦 automacao-formulario<br>
├── produtos.csv<br>
├── preenchedor.py<br>
└── README.md


---

## 📋 Exemplo de dados (`produtos.csv`)

| código      | marca      | tipo      | categoria | preco_unitario | custo | obs               |
|-------------|------------|-----------|-----------|----------------|--------|-------------------|
| MOLO000251  | Logitech   | Mouse     | 1         | 25.95          | 6.5    |                   |
| CAHA000252  | Hashtag    | Camisa    | 2         | 25.00          | 11.0   | Conferir estoque  |
| CEMO000223  | Motorola   | Celular   | 3         | 229.00         | 55.0   |                   |
| ...         | ...        | ...       | ...       | ...            | ...    | ...               |

---

## 🛠️ Tecnologias utilizadas

- [Python](https://www.python.org/)
- [Pandas](https://pandas.pydata.org/)
- [Selenium](https://selenium.dev/)
- [Webdriver Manager](https://pypi.org/project/webdriver-manager/)

---

## ⚙️ Como instalar e rodar

### 🔧 Instale as bibliotecas necessárias:

- pip install selenium
- pip install webdriver-manager
- pip install pandas
---
### 🚀 Funcionamento
O script:

- Lê os dados do arquivo produtos.csv

- Abre um navegador com Selenium

- Acessa um formulário do Google

- Preenche os campos automaticamente com base em cada linha do CSV

- Envia o formulário e repete para a próxima linha

- Um break foi adicionado como teste após 3 envios (remova para executar todos)

  ---
### ⚠️ Cuidados

- Certifique-se de que os XPaths estão atualizados — formulários do Google podem mudar a estrutura.

- O Selenium simula um navegador real, então tempo (sleep) entre ações é necessário para evitar erros.

---
### 📄 Licença
- Este projeto está sob a licença MIT. Sinta-se à vontade para utilizar, modificar e compartilhar.



