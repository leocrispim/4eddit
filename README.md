Status do Projeto: Concluido :heavy_check_mark:

## Leonardo Crispim

**Canais de comunicação**:
- [Linkedin](https://www.linkedin.com/in/leonardo-crispim-371a23134/)
- [Github](https://github.com/leocrispim)
- <leonardo.crispim@outlook.com.br>
## Labenu | Full-Stack Web Development Bootcamp (Anteriormente Future4)
Desenvolvimento de aplicações completas, incluindo frontend Web com React e backend com Node.js.
[![Screenshot_1](https://github.com/leocrispim/stuff/blob/master/Lbn.png)](https://www.labenu.com.br/)
# FutureEats
<br>

<p align="center">
  <img alt="GitHub top language" src="https://img.shields.io/github/languages/top/leocrispim/4eddit">
  <img alt="GitHub language count" src="https://img.shields.io/github/languages/count/leocrispim/4eddit">
  <img alt="Repository size" src="https://img.shields.io/github/repo-size/leocrispim/4eddit">
  <a href="https://github.com/leocrispim/4eddit/commits/master">
    <img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/leocrispim/4eddit">
  </a>
</p>

<br>

#### Escopo do Projeto

Essa semana, vocês irão implementar uma rede social! Já fizemos vários protótipos de redes sociais, mas nenhuma delas realmente funcional. A ideia agora é fazer uma rede real, com cadastro, login, posts, likes e comentários. Para isso, iremos nos basear no **[reddit.com](https://reddit.com).**

A rede social terá 4 páginas:

### Página de login
![1](https://user-images.githubusercontent.com/3521896/77802249-3ada3280-7059-11ea-9da7-5762c6daf97d.png)

A página de login possui dois campos de texto: email e senha. O comportamento será o mesmo da página de login feita semana passada. Ao fazer o login, o usuário deverá ser redirecionado para a página de feed.

A página possui também um botão "Cadastrar", que leva o usuário para a página de cadastro.

### Página de cadastro

![2](https://user-images.githubusercontent.com/3521896/77802253-3ca3f600-7059-11ea-8bc9-e43db687e62c.png)

A página de cadastro possui 3 campos: nome de usuário, email e senha. O endpoint de cadastro retornará as mesmas informações do endpoint de login. Portanto, após cadastrar, o usuário deverá ser redirecionado para a página de feed, já estando logado (ou seja, com o token salvo no LocalStorage).

### Página de feed (lista de posts)

![3](https://user-images.githubusercontent.com/3521896/77802257-3e6db980-7059-11ea-9978-cc4612e444a1.png)

A página de feed deverá mostrar todos os posts, além de um formulário para a criação de post. O formulário possui apenas o campo de texto. Cada post mostrará o nome de usuário que postou, o texto do post, o número de votos (positivo ou negativo) e o número de comentários. Caso o usuário tenha votado positiva ou negativamente, isso deverá estar indicado. Todas essa informações serão fornecidas pela API.

Quando o usuário clicar em um post, ele deverá ser redirecionado para a página do respectivo post. 

Quando um usuário clicar em votar (positiva ou negativamente), uma requisição deverá ser feita indicando a "direção" do voto. Um voto positivo é indicado com o número `1`. Um voto negativo é indicado com o número `-1`. Para remover um voto, a direção deve ser `0`.

Essa página só pode ser acessada por um usuário logado. Caso o usuário não esteja logado, deverá ser redirecionado para a página de login.

### Página de post

![4](https://user-images.githubusercontent.com/3521896/77802261-40377d00-7059-11ea-8f65-2b305bf5e6f8.png)

A página de um post mostrará o mesmo card de post da página de feed, com o usuário, texto, curtidas e número de comentários. Abaixo, terá um formulário para criação de comentários e os cards de comentários. A estrutura é muito similar à do post, mas comentários não possuem outros comentários dentro deles. A lógica de votos é a mesma do post.

Essa página só pode ser acessada por um usuário logado. Caso o usuário não esteja logado, deverá ser redirecionado para a página de login.
<br>

### Linguagens
* HTML
* JavaScript
* CSS (Em styled-components)
### Tecnologias/Ferramentas
* Git
* BrowserDevTools
* Node.js
* React
* Redux
* Surge
* Estilização Avançada com CSS
* Responsividade e adaptação de aplicação web para front.
### O que a plataforma é capaz de fazer :checkered_flag:
:trophy: Simular o funcionamento e aparência de uma rede social baseada no **[reddit.com](https://reddit.com).**
<br>
:trophy: Salvar, sincronizar e gerenciar posts, comentarios, likes e dislikes de múltiplos usuários simultaneamente.
### Linguagens e libs utilizadas :books:
- [React](https://pt-br.reactjs.org/): versão 16.12.0
- [Styled Components](https://styled-components.com/): versão 5.0.0
- [@material-ui/core](https://material-ui.com/): versão 4.8.3
- [@material-ui/icons](https://material-ui.com/pt/components/material-icons/): versão 4.5.1
- [axios](https://github.com/axios/axios): versão 0.19.1
- [connected-react-router](https://github.com/supasate/connected-react-router): versão 6.6.1
- [history](https://github.com/ReactTraining/history): versão 4.10.1
- [react-redux](https://react-redux.js.org/): versão 7.1.3
- [react-router-dom](https://www.npmjs.com/package/react-router-dom): versão 5.1.2
- [redux](https://redux.js.org/): versão 4.0.5
- [redux-thunk](https://www.npmjs.com/package/redux-thunk): versão 2.3.0

### Como rodar a aplicação :arrow_forward:
No terminal, clone o projeto: 
```
git clone https://github.com/leocrispim/4eddit.git
```
Navegue para dentro da raiz do projeto
```
cd 4eddit
```
Instale as dependências
```
npm i
```
Execute a aplicação
```
npm start
```
Você poderá acessar a aplicação em [localhost:3000](http:localhost:3000)
**Projeto inicialmente desenvolvido em 07/04/2020 em parceria com:**
* [Dennis Alves](https://github.com/DennisAlves)
* [Henrique Mendes](https://github.com/hdmendes)
### RESULTADO FINAL
[Site do projeto](http://leocrispim4eddit.surge.sh)
<br>
<br>
**OBS:** Projeto desenvolvido em **desktop first**, portanto melhor visualizado em telas de computador e/ou de tamanho similar.
