# 💱 Cotação de Moedas - AwesomeAPI

Este é um aplicativo simples desenvolvido com [Streamlit](https://streamlit.io/) que permite consultar em tempo real a cotação de moedas utilizando a [AwesomeAPI](https://docs.awesomeapi.com.br/api-de-moedas).

## 📷 Preview

<!-- Substitua o link abaixo por uma imagem ou gif do app rodando -->
![demo](https://user-images.githubusercontent.com/your-demo-image.png)

---

## 🚀 Funcionalidades

- Consulta em tempo real das seguintes moedas:
  - Dólar → Real (USD-BRL)
  - Euro → Real (EUR-BRL)
  - Bitcoin → Real (BTC-BRL)
  - Libra → Real (GBP-BRL)
- Exibe:
  - Nome da cotação
  - Alta e baixa do dia
  - Variação
  - Cotação atual de compra e venda

---

## 🛠 Tecnologias utilizadas

- [Python](https://www.python.org/)
- [Streamlit](https://streamlit.io/)
- [Requests](https://docs.python-requests.org/)
- [AwesomeAPI](https://docs.awesomeapi.com.br/)

---

## ▶️ Como executar

1. **Clone o repositório:**

```bash
git clone https://github.com/seu-usuario/seu-repositorio.git
cd seu-repositorio
```

2. **Crie um ambiente virtual (opcional, mas recomendado):**

```bash
python -m venv venv
source venv/bin/activate  # Linux/Mac
venv\Scripts\activate     # Windows
```

3. **Instale as dependências:**

```bash
pip install -r requirements.txt
```

> **Dica:** Você pode gerar um arquivo `requirements.txt` com:
> ```bash
> pip freeze > requirements.txt
> ```

4. **Execute o aplicativo:**

```bash
streamlit run app.py
```

---

## 🧠 Estrutura do Código

```python
moedas = {
    "Dólar → Real": "USD-BRL",
    "Euro → Real": "EUR-BRL",
    "Bitcoin → Real": "BTC-BRL",
    "Libra → Real": "GBP-BRL"
}
```

- O usuário escolhe uma moeda no menu suspenso.
- Ao clicar em **Buscar cotação**, é feita uma requisição para a AwesomeAPI.
- Os dados retornados são exibidos de forma clara e direta na interface.

---

## 📌 Requisitos

- Python 3.7+
- Conexão com a internet (para chamadas à API)

---

## 📄 Licença

Este projeto está sob a licença [MIT](LICENSE).

---

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se livre para abrir issues ou enviar pull requests.

---

## 📫 Contato

Se tiver dúvidas, sugestões ou quiser trocar uma ideia:

- [Seu Nome](https://github.com/seu-usuario)
- Email: seuemail@exemplo.com
