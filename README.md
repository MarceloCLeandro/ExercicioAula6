# Exercicio Aula 6

 Continuação

 Iremos continuar a utilização do SiteCSS.
 
 No arquivo de estilo do site, crie um seletor para que os elementos input com o tipo “text” fiquem com uma margem maior abaixo deles.

     input[type="text"] { margin-bottom: 10px }
 
 Ajuste também para que os botões do formulário fiquem com uma margem maior no topo e o texto fique com a cor azul.
 
    input[name^="btn"] {margin-top: 10px; color: rgb(0,0,255) }

Exercício - Overflow

Vamos adicionar um seletor de classe para o parágrafo que possui as demais imagens na página fotos.html.

Este seletor irá delimitar o tamanho do parágrafo e setaro overflow para auto, exibindo uma barra de rolagem.

    .demaisFotos{
        overflow: auto;
        width: 80%
        height: 400px;
    }

Utilize o seletor de classe criado na parágrafo das demais fotos.


Exercício - Float

Altere os seletores das divsdas fotos do SiteCSScom as seguintes propriedades:

    figure.thumb{ border: 1px dashedblack; margin:10px; float:left}

Vejam que as imagens estão flutuando à esquerda agora, porém todo o conteúdo está seguindo a flutuação. Para ajustar o layout coloque a propriedade clear:bothdentro do elemento <hr/> logo acima do parágrafo “Mais imagens”        

    <hr style="clear:both“ >

Exercício – Float(2)

No arquivo “biografia.html”:

Adicione de forma “inline” o estilo abaixo para a tagde imagem do Luís Fernando Veríssimo:

    style="float:right"

Exercício – Float(3)

No arquivo “estilo.css” do SiteCSS:

Crie os seguintes seletores com estas propriedades:
    
    nav{ float: left;  width: 100px; }
    #containerConteudo{ float: left; width: 800px; margin-left:5px; margin-top: 10px}
    footer{ clear:both; }
    
Nos arquivos html ajuste as tags para utilizarem corretamente os seletores. Sabendo que:

nav possui os links de navegação

O containerConteudoé a section principal do html, criada logo após o final do menu de navegação. Deve ser criada a propriedade id=“containerConteudo” para ela.

footeré a tagde rodapé dos arquivos html. 