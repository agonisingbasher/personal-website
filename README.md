# Felipe Alexandre — Portfólio Pessoal

Bem-vindo ao repositório do meu portfólio pessoal e profissional. O site reúne minha apresentação, meus projetos de desenvolvimento e engenharia reversa, além de canais para contato e acompanhamento do meu trabalho.

- **Aluno:** Felipe Alexandre
- **Site publicado:** https://agonisingbasher.github.io/personal-website/
- **Repositório:** https://github.com/agonisingbasher/personal-website

## Sobre o portfólio

O portfólio foi criado para apresentar minha trajetória como desenvolvedor independente, estudante e criador de conteúdo. A página inicial apresenta meu perfil, projetos em destaque e formas de contato.

## Seções do site

- **Perfil / Sobre mim:** apresentação pessoal, interesses e áreas de atuação.
- **Projetos:** projetos de desenvolvimento e pesquisa, incluindo Stardew Valley para Wii U, FNAF 2 para Nintendo DSi e Ocarina of Time para Nintendo DSi.
- **Contato:** links para GitHub, YouTube, LinkedIn e meu site de conteúdo.
- **Navegação:** menu com links para as seções da própria página e controles para alternar o idioma.

## Tecnologias utilizadas

- HTML5 — estrutura e conteúdo das páginas.
- CSS3 — identidade visual, animações, efeitos de interação e responsividade.
- JavaScript (ES6+) — interações e sistema de tradução.
- **Bootstrap 5.3.8** — framework CSS utilizado no layout responsivo da área de projetos, com sistema de linhas e colunas (row, g-4, col-12 e col-lg-6).
- GitHub Pages — publicação e hospedagem do site.

## Funcionamento do projeto

A página principal é construída em HTML. Os estilos próprios ficam em style.css, enquanto as interações e traduções ficam em script.js.

O Bootstrap é carregado pelo CDN no head, antes da folha de estilos própria. Na seção de projetos, as classes row, g-4, col-12 e col-lg-6 organizam os cartões em uma coluna em telas menores e em duas colunas em telas grandes. O CSS do projeto complementa o framework e preserva a identidade visual personalizada.

## Recurso adicional: site multilíngue

Além das seções e da navegação, o portfólio possui um sistema próprio de idiomas. O visitante pode escolher entre português brasileiro (pt-BR), inglês (EN), espanhol (ES) e francês (FR) pelos botões no cabeçalho.

O idioma pode ser definido pelo parâmetro ?lang= na URL, por uma escolha salva no navegador ou pelas preferências de idioma do navegador. A escolha manual é armazenada em localStorage, permitindo que seja mantida em visitas posteriores.

### Como o recurso foi implementado

O recurso foi desenvolvido em JavaScript no arquivo script.js, utilizando dicionários de tradução para cada idioma. Os elementos da página que possuem o atributo data-i18n são atualizados com os textos correspondentes ao idioma selecionado. A preferência é salva com localStorage e o parâmetro lang da URL também é atualizado para permitir links que abram o site em um idioma específico.

## Publicação

O projeto é publicado pelo GitHub Pages:

**https://agonisingbasher.github.io/personal-website/**

---

Desenvolvido por **Felipe Alexandre**.
