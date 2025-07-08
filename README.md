# 🛡️ Centrarmory

Este projeto faz parte da fase 6 do trabalho de armazenamento de base militar.  
Aqui, implementamos uma camada de acesso a dados utilizando **ORM (SQLAlchemy)** sem alterar o banco que foi projetado nas fases anteriores.


---

## 📁 Estrutura do Projeto

```
CTM/
├── app.py 
├── crud.py 
├── models.py 
├── queries.py 
├── SQL.txt 
└── README.md 
```


## 💻 Como Rodar o Projeto Localmente

Passos para testar o projeto:

1️⃣ Instalar dependências 

    pip install sqlalchemy

2️⃣ Criar e popular o banco de dados  

    Get-Content .\SQL.txt | sqlite3.exe centrarmory.db

3️⃣ Rodar o código Python

    python app.py

---

## ✍️ Observações

* A conexão é feita via SQLAlchemy no arquivo models.py //engine = create_engine
* ter o sqlite(3.exe) e colocar nos patch de ambiente
---

## 📌 Autores

* Gabriel Dias -- RA2515571
* Felipe Salazar -- RA2515563
* Marcus Zabla -- RA2504529
---

## 📄 Licença

Este projeto é apenas para fins acadêmicos.
