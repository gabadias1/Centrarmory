# 🛡️ Centrarmory

**Centrarmory** é um sistema web para cadastro, controle de estoque e movimentação de materiais militares (como armas, munições, vestimentas, explosivos, suprimentos e acessórios), incluindo gerenciamento de efetivos.

---

## 🚀 Funcionalidades

* Cadastro de diferentes tipos de itens
* Controle de estoque centralizado
* Movimentações de entrada/saída por efetivos
* Cadastro e listagem de efetivos com dados completos
* Visual moderno com CSS customizado

---

## 📁 Estrutura do Projeto

```
centrarmory/
├── app.py                 
├── models.py            
├── centrarmory.db  
├── static/
│   └── style.css      
├── templates/
│   ├── index.html
│   ├── estoque.html
│   ├── historico.html
│   ├── movimentar.html
│   ├── cadastrar_usuario.html
│   ├── selecionar_item.html
│   └── cadastrar_item_*.html  # Um arquivo para cada tipo de item
└── README.md
```

---

## 🧩 Tecnologias Usadas

* Python 3.10+
* Flask
* SQLAlchemy
* SQLite (local)
* HTML + CSS

---

## 💻 Como Rodar o Projeto Localmente

### 1. Clone o projeto ou copie a pasta:

```bash
git clone https://github.com/seuusuario/centrarmory.git
cd centrarmory
```

### 2. Crie o ambiente virtual:

```bash
python -m venv venv
```

### 3. Ative a venv:

No **Windows**:

```bash
venv\Scripts\activate
```

### 4. Instale as dependências:

```bash
pip install flask sqlalchemy
```

### 5. Crie o banco de dados:

```bash
python models.py
```

### 6. Rode o sistema:

```bash
python app.py
```

### 7. Acesse no navegador:

```
http://localhost:5000
```

---

## ✍️ Observações

* O banco de dados será criado com dados fictícios para testes.
* Todos os arquivos HTML estão no diretório `templates/` e já seguem o estilo unificado.

---

## 📌 Autores

Gabriel Dias -- RA:2515571
Felipe Salazar -- RA2515563
Marcus Zabla -- RA2504529
---

## 📄 Licença

Este projeto é apenas para fins acadêmicos.
