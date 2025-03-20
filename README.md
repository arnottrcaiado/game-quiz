# 📕 Seu Jogo de Quiz com Python, Flask e PythonAnywhere

🎮 **Público-alvo:**  
Introdutório. Estudantes de graduação em Jogos Digitais e Análise de Sistemas, com conhecimento básico em lógica de programação e HTML.

## ✅ 1. Introdução

O objetivo deste é conduzir você na criação de um jogo de quiz web usando Flask, com uma interface interativa em HTML, CSS e JavaScript, e disponibilizá-lo online com PythonAnywhere.

O projeto será construído de forma modular, aplicando conceitos de prototipação rápida.

---

## 🧠 2. O que é um jogo de quiz?

Um quiz é um jogo baseado em perguntas e respostas.

Possibilita diversas abordagens: múltipla escolha, verdadeiro ou falso, cronômetro, ranking etc.

Vamos criar uma versão básica que pode ser expandida.

---

## 🧱 3. Visão geral do projeto

- **Backend:** Python + Flask  
- **Frontend:** HTML + CSS + JS  
- **Armazenamento:** JSON  
- **Hospedagem:** PythonAnywhere  

---

## 🧰 4. Preparando o ambiente

1. Instale o Python (recomenda-se versão 3.10 ou superior)  
2. Instale o Flask com:  
   ```bash
   pip install flask
   ```
3. Crie a estrutura de pastas do projeto:
   ```
   /quiz-flask-game
   ├── static/
   ├── templates/
   ├── app.py
   ├── questions.json
   └── requirements.txt
   ```

---

## 🧪 5. Criando a estrutura base com Flask

- Arquivo principal: `app.py`
- Rota principal: `@app.route('/')`
- Renderização: `render_template('index.html')`

---

## 🖼️ 6. Criando o frontend com HTML, CSS e JS

- `index.html` com estrutura básica
- `script.js` para carregar perguntas e interações (use `fetch` para JSON)

---

## 📂 7. Lógica do quiz (JS)

- Mostra uma pergunta por vez  
- Botões de resposta  
- Contador de acertos  
- Opção de reiniciar o quiz  

---

## 🧾 8. Salvando e carregando perguntas

- Arquivo: `questions.json`  
- Estrutura:
```json
[
  {
    "question": "Qual é a capital do Brasil?",
    "options": ["São Paulo", "Brasília", "Curitiba"],
    "answer": "Brasília"
  }
]
```

---

## 🌐 9. Prototipando com GitHub

1. Crie um repositório (ex: `quiz-flask-game`)  
2. Faça `git init`, `git add`, `git commit`, `git remote add origin`, `git push`

---

## 🚀 10. Deploy no PythonAnywhere

1. Acesse [www.pythonanywhere.com](https://www.pythonanywhere.com)
2. Crie uma nova web app com Flask
3. Configure o caminho para `app.py`
4. Crie `requirements.txt` com:
   ```
   flask
   ```

---

## 🔗 11. Conectando GitHub ao PythonAnywhere

1. No console do PythonAnywhere, clone seu repositório:
   ```bash
   git clone https://github.com/seuusuario/quiz-flask-game.git
   ```
2. Aponte o caminho do Flask App no painel Web:
   ```
   /home/seuusuario/quiz-flask-game/app.py
   ```
3. Reinicie a aplicação.

---

## 🔄 12. Melhorias futuras

- Sistema de login  
- Banco de dados com Flask-SQLAlchemy  
- Temporizador por pergunta  
- Ranking e pontuação final  
- Suporte a múltiplos idiomas  
- Integração com APIs externas ou sensores IoT  

---

## 📚 13. Recursos úteis

- [Flask Docs](https://flask.palletsprojects.com/)  
- [PythonAnywhere Help](https://help.pythonanywhere.com/)  
- [MDN Web Docs (JS, HTML, CSS)](https://developer.mozilla.org/)  

---

## 🏁 14. Conclusão

Você construiu um jogo de quiz do zero com Flask, usou boas práticas de organização e hospedou sua aplicação gratuitamente.

A partir daqui, você pode personalizar, adicionar sensores, criar rankings e integrar com APIs!

---

## 🧩 15. Arquitetura do Projeto

### 🔧 Backend (Python + Flask)
- Controla as rotas e lógica principal da aplicação.
- Responsável por servir os arquivos HTML e JSON.

### 🎨 Frontend (HTML + CSS + JS)
- Responsável pela interação com o usuário.
- Usa `fetch()` para buscar os dados do quiz em JSON.
- Gerencia a lógica do jogo, exibição de perguntas e contagem de pontos.

### 📁 Armazenamento (JSON)
- Armazena perguntas de forma simples.
- Fácil de editar e manter sem necessidade de banco de dados.

### ☁️ Git + GitHub
- Versionamento de código.
- Compartilhamento e backup do projeto.

### 🌍 PythonAnywhere
- Hospedagem gratuita para aplicações Flask.
- Integração simples com GitHub.
