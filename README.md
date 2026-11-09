# 🎵 Sistema Musical - Web Application

Este é um projeto de um **Sistema Musical** desenvolvido como atividade prática para a disciplina de **Linguagem de Marcação**. O objetivo da aplicação é simular uma plataforma de música com cadastro de artistas, cadastro de músicas, controle de acesso e visualização do catálogo.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5:** Estruturação semântica de todas as páginas da aplicação.
* **CSS3:** Estilização global e customização das páginas (`style.css`).
* **VS Code:** Ambiente de desenvolvimento integrado (IDE) utilizado para a escrita e testes do código.

---

## 🚀 Etapas e Desenvolvimento no VS Code

O projeto foi dividido e construído em **5 etapas/páginas principais**, com todo o código estruturado via **VS Code**:

### 1. Página Inicial (`index.html`)
* **Descrição:** Página de abertura do sistema (Dashboard/Home).
* **Desenvolvimento no VS Code:**
  * Criação da estrutura base com HTML5 (`! + Tab`).
  * Adição de menu de navegação (`<nav>`) para direcionar o usuário às outras páginas.
  * Seção principal (`<main>`) com banner de boas-vindas e destaques da plataforma.

### 2. Cadastro de Artista (`cadastro_artista.html`)
* **Descrição:** Formulário para registrar novos cantores, bandas ou DJs na plataforma.
* **Desenvolvimento no VS Code:**
  * Construção do formulário usando a tag `<form>`.
  * Inserção de campos de entrada como nome do artista, gênero musical, país de origem e foto/banner.
  * Implementação de botões de submissão (`<button type="submit">`) e validações básicas dos campos (`required`).

### 3. Cadastro de Música (`cadastro_musica.html`)
* **Descrição:** Formulário dedicado ao envio e registro de novas faixas musicais no sistema.
* **Desenvolvimento no VS Code:**
  * Estruturação de campos para título da música, artista responsável (usando `<select>` ou `<input>`), álbum, ano de lançamento e duração.
  * Organização dos rótulos (`<label>`) e inputs para melhor acessibilidade e usabilidade.

### 4. Listagem de Músicas (`listagem_musicas.html`)
* **Descrição:** Galeria/tabela onde são exibidas as músicas cadastradas no catálogo.
* **Desenvolvimento no VS Code:**
  * Utilização de elementos de tabela (`<table>`, `<tr>`, `<th>`, `<td>`) ou grid de cards para listar o acervo.
  * Organização de informações como título, artista, gênero e botões para ouvir/ações.

### 5. Página de Login (`login.html`)
* **Descrição:** Tela de autenticação para entrada dos usuários no sistema.
* **Desenvolvimento no VS Code:**
  * Criação da interface simples e funcional de login.
  * Campos para e-mail/usuário e senha (`type="password"`).
  * Links para recuperação de senha e botão de validação de acesso.

---

## 🎨 Estilização Global (`style.css`)

A identidade visual do sistema foi centralizada em um único arquivo de folha de estilo (`style.css`), importado em todas as páginas HTML:

* Padronização de cores, tipografia e espaçamentos (Reset CSS).
* Estilização moderna de formulários, tabelas e botões interativos.
* Layout responsivo adaptado para diferentes tamanhos de tela.

---

## 📂 Estrutura de Arquivos

```text
.
├── index.html
├── cadastro_artista.html
├── cadastro_musica.html
├── listagem_musicas.html
├── login.html
└── style.css
```

---

## 👨‍💻 Autor

Projeto desenvolvido por **Riquelme Reis** na matéria de **Linguagem de Marcação**.
