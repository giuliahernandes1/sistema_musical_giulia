# 🎵 Sistema Musical - Catálogo de Artistas e Músicas

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![SENAI](https://img.shields.io/badge/SENAI_SP-2026-red?style=for-the-badge)

Projeto desenvolvido durante o 2º Semestre de 2026 no curso **Técnico em Desenvolvimento de Sistemas - SENAI SP**, referente à **Sprint 1 (Front-end)** da unidade curricular de **Linguagem de Marcação (LIMA)**.

---

## 📌 Sobre o Projeto

O **Sistema Musical** é um catálogo digital para gerenciamento e navegação de artistas e suas respectivas obras musicais. O foco principal desta primeira entrega foi a construção da interface do usuário (UI/UX) utilizando apenas **HTML5 e CSS3 puro**, aplicando práticas modernas de layouts semânticos, flexíveis e responsivos sem o uso de frameworks externos.

> ℹ️ **Nota:** Nesta Sprint 1, os dados exibidos nas telas são estáticos e os formulários possuem validação nativa HTML5. O desenvolvimento da camada back-end (PHP, Banco de Dados MySQL e autenticação real) será integrado na Sprint 2.

---

## 🖥️ Telas do Sistema (Fluxo de Navegação)

O projeto é composto por **5 telas interconectadas**:

1. **🔑 Login (`login.html`)**: Tela de autenticação inicial centralizada, com campos de usuário e senha obrigatórios, além da indicação de credenciais de teste (`admin` / `123`).
2. **🏠 Menu Principal (`index.html`)**: Painel de navegação com saudação ao usuário, botão de logout e cards responsivos para acesso rápido às funcionalidades.
3. **🎼 Biblioteca Musical (`listagem_musicas.html`)**: Listagem das músicas cadastradas em tabela, com barra de pesquisa geral, filtros por artista e gênero, link para reprodução externa (YouTube em nova aba) e botões de ação (editar/excluir).
4. **🎤 Cadastro de Artistas (`cadastro_artista.html`)**: Formulário em 2 colunas para cadastro de criadores com campo para upload de imagem e tabela de exibição.
5. **🎵 Cadastro de Músicas (`cadastro_musica.html`)**: Formulário em 2 colunas com seleção de artista, link externo, campo de arquivo e área de observações (`textarea`), acompanhado da tabela das obras já cadastradas.

---

## 🚀 Tecnologias e Conceitos Utilizados

- **HTML5 Semântico**: Estruturação limpa e acessível de cabeçalhos, formulários, tabelas e seções.
- **CSS3 Puro**:
  - **Variáveis CSS (`:root`)**: Padronização da identidade visual (paleta de cores, tipografia e bordas).
  - **Flexbox & CSS Grid**: Construção de layouts flexíveis e alinhamentos de cartões e formulários.
  - **Design Responsivo (`@media`)**: Layout adaptável para telas móveis ($\le 768\text{px}$), reorganizando formulários em coluna única e permitindo rolagem horizontal em tabelas.
  - **Estilização Global**: Arquivo único `style.css` compartilhado por todas as páginas.

---

## 📁 Estrutura de Arquivos

```text
├── index.html               # Menu Principal
├── login.html               # Tela de Login
├── listagem_musicas.html    # Biblioteca / Listagem de Músicas
├── cadastro_artista.html    # Cadastro e Listagem de Artistas
├── cadastro_musica.html     # Cadastro de Músicas
├── style.css                # Folha de estilo global
└── README.md                # Documentação do repositório
