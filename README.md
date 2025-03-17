- Navbar com Animação de Bolha -

Introdução:
Este projeto é uma navbar responsiva com animação de bolha, criada usando HTML, CSS e JavaScript. O menu inclui um botão hambúrguer que, ao ser clicado, revela os links de navegação com uma animação circular, proporcionando uma interação dinâmica e moderna.

Funcionalidades - 
Menu Hambúrguer: Aparece em dispositivos com largura de tela abaixo de 750px, permitindo o acesso ao menu de navegação.
Animação de Bolha: O menu desliza e aparece com uma animação circular suave quando o menu hambúrguer é clicado.
Design Limpo e Moderno: Utiliza a fonte "Fredoka One" e cores vibrantes, como o verde água e roxo, para uma experiência visual atraente.

Aqui está um resumo básico de como o efeito foi implementado:

- HTML:
A estrutura da navbar contém um botão hambúrguer (<button class="hamburger">) e uma lista de navegação (<ul class="nav-list">), com links de navegação.
A classe .logo é usada para exibir o nome ou logo do site.

- CSS:
Menu Hambúrguer: O botão hambúrguer é composto por três barras (::before, ::after e o próprio hamburger). Quando clicado, ele faz uma animação para formar um "X".
Responsividade: A navbar usa @media queries para exibir o menu hambúrguer em telas pequenas. Em dispositivos móveis, a lista de navegação é inicialmente oculta, sendo exibida com uma animação circular utilizando clip-path para dar o efeito de "bolha" ao expandir o menu.
Transições: Transições suaves (transition) são aplicadas para animações de entrada e saída dos links no menu.

- JavaScript:
O código JavaScript escuta o clique no botão hambúrguer e adiciona ou remove a classe .active da navbar. Quando essa classe é adicionada, a lista de navegação aparece com a animação de bolha (expansão circular), e o botão hambúrguer se transforma em um "X" para indicar o fechamento do menu.

Esse conjunto de tecnologias cria uma navbar dinâmica e interativa, onde o efeito de bolha e a transformação do botão hambúrguer tornam a experiência do usuário mais interessante.
