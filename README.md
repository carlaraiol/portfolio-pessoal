# Portfólio Profissional

## 📋 Descrição do Projeto
Este projeto consiste no desenvolvimento de um portfólio web pessoal e responsivo, criado com o objetivo de apresentar habilidades técnicas e projetos desenvolvidos ao longo da formação no curso técnico.

## 🛠️ Tecnologias Utilizadas
* **HTML5:** Linguagem de marcação para estruturação das páginas
* **CSS3:** Estilização visual e customizações complementares
* **Bootstrap 5.3.3:** Framework CSS para criação rápida de layouts responsivos e componentes modernos (Navbar, Carousel, Cards, Grid)
* **Devicon:** Biblioteca de ícones para representação visual das tecnologias
* **Git e GitHub / GitHub Pages:** Controle de versão e hospedagem online do site

## 🔗 Link do Portfólio
Você pode acessar o site em funcionamento através do link do GitHub Pages:
https://carlaraiol.github.io/portfolio-pessoal/

## ⚙️ Explicando o site
O site é estruturado em uma página única (*Single Page Application*), organizada nas seguintes seções:
1. **Navbar (Menu Superior):** Menu fixo no topo (`sticky-top`) com links de navegação interna que rodam suavemente até as respectivas seções.
2. **Carousel:** Área de destaque visual em slides com transição suave (`carousel-fade`) localizada logo abaixo do menu.
3. **Seção Perfil:** Apresentação pessoal com foto em destaque, biografia, cards informativos e grade de competências/ferramentas técnicas.
4. **Seção Projetos:** Exibição em formato de cards responsivos de 3 principais trabalhos desenvolvidos, contendo imagens ilustrativas, descrições e botões de acesso.
5. **Seção Contato:** Bloco centralizado contendo botões interativos de redirecionamento para E-mail e GitHub.
6. **Rodapé (Footer):** Informações finais de direitos autorais e créditos de desenvolvimento.

## 🚀 Descrição do Novo Recurso
Para ir além do modelo base ensinado em sala de aula, foi adicionado um recurso de animação e efeito de hover customizado em CSS aplicado interativamente sobre todos os blocos de cards do site (incluindo cards de perfil, ferramentas e projetos).

## 💡 Explicação de Implementação
O recurso foi integrado diretamente no cabeçalho do arquivo `index.html` utilizando as propriedades de transição e transformação do CSS3:
* Foi aplicada a regra `.card { transition: transform 0.3s ease, box-shadow 0.3s ease; }` para garantir que qualquer mudança de estado ocorra de forma fluida e suave ao longo de 0.3 segundos.
* Foi utilizada a pseudoclasse `.card:hover { transform: translateY(-8px); box-shadow: 0 1rem 2rem rgba(0, 0, 0, 0.15) !important; }`, que faz com que o card se eleve levemente para cima (`translateY(-8px)`) e ganhe uma sombra mais profunda e elegante sempre que o cursor do mouse passa por cima dele, melhorando a experiência visual e a interatividade do usuário.
