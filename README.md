# 📚 Livros na Prateleira

Um sistema simples para cadastrar e listar seus livros, usando HTML, CSS, JavaScript e um back end Node.js com Express.
—------------------------------------------------------------------------------------------------------------------------
## 🚀 Funcionalidades

- Cadastro de livros com:
  - ID
  - Título
  - Autora
  - Preço
  - Estrelas (0 a 5)
  - Descrição
- Estilização escura com roxo e branco
- Listagem dinâmica de livros cadastrados
—------------------------------------------------------------------------------------------------------------------------
## 📂 Estrutura do Projeto

```bash
/
├── index.html
├── style.css
├── script.js
├── server.js (backend)
└── README.md
—------------------------------------------------------------------------------------------------------------------------

## 🛠️ Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- Node.js + Express (Backend)
- [SQL ou outro banco, se usar]
—------------------------------------------------------------------------------------------------------------------------

## 🖼️ Preview


—------------------------------------------------------------------------------------------------------------------------

COMO USAR

INSTALE AS DEPENDÊNCIAS

(no terminal) Execute:
npm install
npm install fastify
npm run dev
—------------------------------------------------------------------------------------------------------------------------

Abra e clique ‘iniciar tudo’ na aplicação ‘Laragon’.
Na aplicação ‘MYSQL workbench’ crie uma nova conexão com o nome ‘localhost’, nela rode em um novo ‘schema’ o seguinte código:

create database biblioteca;
use biblioteca;

create table livros(
id int primary key not null,
titulo varchar(200) not null,
autora varchar(200) not null,
preço float,
estrelas tinyint not null,
descrição varchar(800)
);

—------------------------------------------------------------------------------------------------------------------------
Caso queira observar o como os livros aparecem mas não tenha o MYSQL workbench você pode adicionar este trecho de código no index.html, logo após o :
 <section id=”minhalista”></section> 

   <section id="minhalista">
    <h2>Livros cadastrados (Exemplo)</h2>
    <div class="livro-card">
        <h3>A Revolução dos Bichos</h3>
        <p><strong>Autora:</strong> George Orwell</p>
        <p><strong>Preço:</strong> R$ 29,90</p>
        <p><strong>Estrelas:</strong> ⭐⭐⭐⭐</p>
        <p><strong>Descrição:</strong> Uma fábula sobre poder e corrupção entre os animais da fazenda.</p>
    </div>
    <div class="livro-card">
        <h3>Dom Casmurro</h3>
        <p><strong>Autora:</strong> Machado de Assis</p>
        <p><strong>Preço:</strong> R$ 24,90</p>
        <p><strong>Estrelas:</strong> ⭐⭐⭐⭐⭐</p>
        <p><strong>Descrição:</strong> Um clássico sobre ciúme, memória e incertezas narrativas.</p>
    </div>
</section>

Feito com ❤️ por Rayka Neres (https://github.com/rayrayka-bill)
—----------------------------------------------------------------------------------------------------------------------------
