# 🎵 Sistema Musical

Bem-vindo ao repositório do **Sistema Musical**! Este projeto foi desenvolvido inteiramente em sala de aula utilizando o VSCode. O objetivo do sistema é simular um gerenciador de biblioteca musical profissional, com autenticação, estruturação de dados de artistas e um acervo interativo de músicas.

## 🛠️ Etapas do Desenvolvimento e Estrutura do Projeto

O projeto foi dividido em 5 etapas principais. Cada arquivo foi cuidadosamente desenvolvido para cumprir um papel específico dentro da aplicação:

## 1. Autenticação e Acesso (`login.html`)
Foi a primeira etapa do projeto, servindo como a porta de entrada segura do sistema.
* **O que foi desenvolvido:** Formulário de login com campos para Usuário e Senha, lógica visual de feedback (como a caixa verde de alerta ao sair), e indicação de credenciais de teste para facilitar a avaliação.

## 2. Painel Principal / Dashboard (`index.html`)
Após o login, o utilizador é redirecionado para este menu de navegação, que funciona como o "coração" do sistema.
* **O que foi desenvolvido:** Mensagem de boas-vindas dinâmica e um layout baseado em cards interativos com ícones intuitivos, servindo de atalho para todas as funções principais (Gerenciar Artistas, Cadastrar Músicas e Biblioteca Musical).

## 3. Gestão de Artistas (`cadastro_artista.html`)
Uma página dividida em duas áreas fundamentais: entrada de dados e visualização de registos.
* **O que foi desenvolvido:** Formulário completo para inserir Nome, Gênero, País e fazer o upload da Foto do artista. Logo abaixo, uma tabela interativa lista os artistas já cadastrados, contendo botões de ação (Editar, Excluir e Músicas).

## 4. Acervo e Filtros (`cadastro_musica.html` e `listagem_musicas.html`)
O módulo mais robusto do sistema, dividido entre o cadastro de novas faixas e a biblioteca geral.
* **Cadastro de Música:** Formulário detalhado para adicionar uma "Nova Música". Inclui seleção do Artista, Título, Álbum, Gênero, e campos especiais para o Link do YouTube, Capa do Álbum e Letra da Música.
* **Biblioteca Musical:** Criação de uma barra de busca livre e filtros por Artista ou Gênero. A listagem exibe todos os detalhes da faixa (Capa, Título, Álbum, etc.) e inclui um botão de ação especial vermelho (▶ Assistir) integrado à tabela.

## 5. Identidade Visual (`styles.css`)
A última etapa conectou todas as páginas HTML, transformando a estrutura bruta numa aplicação de aparência profissional.
* **O que foi desenvolvido:** Definição de uma paleta de cores moderna (fundo cinza claro, botões coloridos para guiar as ações), bordas arredondadas (*border-radius*), e efeitos visuais (*hover*) para tornar a navegação fluida e agradável.

---

## 👩‍💻 Autoria

Desenvolvido por mim: **Caline Myrella** na disciplina de **Linguagem de Marcação**.
