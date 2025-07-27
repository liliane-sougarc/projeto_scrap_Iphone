
# 📱 Projeto Scrapy - Coleta de Ofertas de iPhone

Este projeto realiza a raspagem automática de dados de ofertas de iPhones em sites públicos de e-commerce.  
É baseado na estrutura didática da **Jornada de Dados**, do Professor **Luciano Galvão Filho**, com ajustes e personalização para fins de portfólio e prática profissional.

---

## 🎯 Objetivo

Criar um **pipeline ETL com Python + Scrapy**, capaz de:
- Extrair dados de produtos de forma automatizada
- Tratar e organizar as informações relevantes
- Armazenar os resultados em formatos reutilizáveis (CSV, JSON, banco de dados)

---

## 🧰 Tecnologias Utilizadas

- Python 3.x
- Scrapy
- VS Code + Terminal
- Git + GitHub

---

## 🗂️ Estrutura Esperada

```
projeto_scrap_Iphone/
├── scrapy.cfg
├── README.md
├── .gitignore
├── projeto_scrap_Iphone/
│   ├── __init__.py
│   ├── items.py
│   ├── pipelines.py
│   ├── settings.py
│   └── spiders/
│       └── iphone_spider.py
```

---

## 🛠️ Como Executar

1. Crie o ambiente virtual:
```bash
python -m venv venv
venv\Scripts\activate  # Windows
```

2. Instale as dependências:
```bash
pip install scrapy
```

3. Execute o spider:
```bash
scrapy crawl iphone_spider
```

4. Para salvar como CSV:
```bash
scrapy crawl iphone_spider -O dados.csv
```

---

## 🙌 Créditos

Projeto baseado no repositório educacional de:
📘 Professor Luciano Galvão Filho  
🔗 https://github.com/lvgalvao/IphoneProjectWebScraping  
📺 Canal: [Jornada de Dados](https://www.youtube.com/channel/UCl-5oPIbTAwLZ0hF_dCUyLQ)

---

## 👩‍💻 Autoria

Este projeto foi adaptado, documentado e publicado por:

**Liliane Garcia**  
Especialista em Tracking, Dados e Automações Digitais  
🔗 [linkedin.com/in/lilianegarcia](https://www.linkedin.com/in/lilianegarcia)

---
