﻿# Projeto-Books

O documento HTML fornecido é uma página da web para uma plataforma relacionada a livros. Inclui um cabeçalho com menu de navegação e links de acesso rápido, uma seção de banner com entrada de pesquisa, carrosséis para novos lançamentos e best-sellers, uma seção para tópicos visitados recentemente, uma seção de contato para inscrição em newsletter e um rodapé com links recursos educacionais e comunidades. A página da web utiliza CSS para estilo, Google Fonts para tipografia e Swiper.js para criar carrosséis responsivos. JavaScript é usado para inicializar Swiper.js para funcionalidade de carrossel. No geral, oferece uma interface amigável para navegar e descobrir livros.

Código CSS. Projetada para normalizar o estilo padrão do navegador em diferentes navegadores. Ele redefine margens, preenchimento e bordas para a maioria dos elementos HTML, define propriedades de fonte para garantir consistência, alinha elementos verticalmente, remove estilos de lista e estilos de cotação padrão e redefine propriedades de layout de tabela. No geral, ele fornece um ponto de partida consistente para estilizar páginas da web, removendo estilos padrão específicos do navegador.
Este código CSS importa vários arquivos CSS externos para diferentes seções de uma página web: cabeçalho, banner, carrossel, tópicos, contato e rodapé. Ele define um conjunto de variáveis ​​CSS personalizadas para cores, fontes e gradientes usando a :rootpseudoclasse. O bodyelemento é estilizado para ter uma cor de fundo, uma família de fonte, tamanho e peso específicos.

Banner.cs > Este código CSS define estilos para a seção de banner de uma página da web. Ele define a cor de fundo para um gradiente linear definido por uma variável personalizada, ajusta a cor do texto, o alinhamento e o preenchimento. Além disso, ele estiliza o título e o texto do banner com tamanhos e pesos de fonte específicos. O campo de entrada de pesquisa é personalizado com estilo de borda, preenchimento e aparência de texto de espaço reservado.

Carrosel.CS > As consultas de mídia são usadas para ajustar os estilos para diferentes tamanhos de tela. Para telas com largura mínima de 1024px, o tamanho da fonte do título do banner e a largura da entrada de pesquisa são aumentados. Para telas com largura mínima de 1728px, ajustes adicionais são feitos na largura de entrada de pesquisa e na posição do texto do espaço reservado, e o preenchimento do banner é aumentado.


Contato.CS >Este código CSS define estilos para uma seção de carrossel em uma página da web. Ele define a cor, a cor de fundo, o alinhamento e as propriedades da fonte do título do carrossel. O estilo dos slides individuais do carrossel, incluindo imagens, é definido. Os botões de navegação (anterior e seguinte) do carrossel estão ocultos. Os indicadores de paginação do carrossel são estilizados e os cartões dentro do carrossel são estilizados com cor de fundo, sombra da caixa, raio da borda, margem e preenchimento.

Além disso, os estilos são definidos para a descrição em cada cartão, incluindo alinhamento, margem e propriedades de fonte. Os botões dentro do cartão, incluindo margem, cor de fundo, preenchimento, cor do texto, espessura da fonte e decoração do texto, são estilizados.

Consultas de mídia são usadas para ajustar estilos para diferentes tamanhos de tela. Para telas com largura mínima de 1024px, o tamanho da fonte do título do carrossel é aumentado, a margem de paginação é ajustada, a largura do carrossel é definida, os botões de navegação são exibidos e a largura e a margem do cartão são ajustadas. Para telas com largura mínima de 1728px, ajustes adicionais são feitos no layout do contêiner do carrossel, na margem de paginação, na largura do carrossel, no tamanho da fonte do título da descrição, no tamanho da fonte do texto de descrição, na largura do cartão, na margem do cartão e na margem direita da descrição.]

Header.cs > incluindo um menu de navegação com um ícone de hambúrguer para dispositivos móveis. Ele define a aparência de vários elementos, como ícone do menu, plano de fundo do cabeçalho, menu de navegação e consultas de mídia para capacidade de resposta. Os estilos garantem que o cabeçalho ajuste seu layout e aparência de maneira eficaz em diferentes tamanhos de tela, proporcionando uma experiência de navegação amigável.

Rodape.cs >  Inclui estilo para o plano de fundo, preenchimento e itens de lista no rodapé. As consultas de mídia são usadas para ajustar o layout e a aparência do rodapé para diferentes tamanhos de tela, tornando-o responsivo. Além disso, os estilos fazem com que o rodapé seja exibido como um contêiner flexível com itens espaçados em telas maiores e ajustam a tipografia e o espaçamento para melhor legibilidade. Por fim, adiciona uma borda para separar o conteúdo do rodapé em telas maiores.


Topico.css > O código CSS fornecido define estilos para uma seção de tópicos. Ele define o plano de fundo com uma cor gradiente, alinha o texto ao centro e aplica preenchimento para espaçamento. Os títulos dos tópicos possuem cor branca com peso reduzido e alguma margem na parte inferior. A lista de tópicos é exibida como um flex container com itens agrupados e alinhamento centralizado. Cada item do tópico tem alguma margem e os links dentro deles têm texto branco sobre fundo laranja com preenchimento e fonte em negrito. Ao passar o mouse, as cores do link são invertidas.

Nas consultas de mídia:

Para telas com largura mínima de 1024px, o tamanho da fonte do título aumenta e o tamanho da fonte do link também é ajustado.
Para telas com largura mínima de 1728px, o preenchimento da seção de tópicos aumenta para abranger 30% da largura da janela de visualização em cada lado.


