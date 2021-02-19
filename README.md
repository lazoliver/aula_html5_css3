# HTML5

* Versão mais nova do padrão HTML;
* HTML é o padrão utilizado para criação de páginas web;
* No HTML5 foram introduzidos novos elementos que proporcionam suporte a maior interatividade com o usuário.



## Aula 1

* Criar um repositório Git 'aula_html5_css3';
* Git clone 'url html do repositório git';
* Criar o arquivo 'index.html'.

## Aula 2

* <*!DOCTYPE html*> Informa ao navegador que o documento é do tipo *HTML5*;
* <*html lang='pt-br'*> Inicia a inserção de dados dentro do documento; lang='pt-br' define que o idioma é português;
* <*head charset="utf-8"*> Armazena as tags de meta dados; charset="utf-8" permite o navegador reproduzir elementos textuais de forma fidedigna;
* <*title*> É o título da página;
* <*body*> Tag que define o conteúdo "corpo" do documento;
* <*p*> Delimita um parágrafo.

## Aula 3

* <*nav*> insere um menu;
* <*ul*> cria uma linha;
* <*li*> cria uma linha;
* <*section id="nome_da_section"*> define uma seção de conteúdo; id="nome_da_section" é utilizado para referenciar essa section;
* <*img* src="img.site.jpg" width="300px"> Tag img adiciona uma imagem; src determina o local da imagem no tipo string; width determina o tamanho da imagem.

## Aula 4

* <*div*> Criar organização na sua página
* <*a href="#servicos"*> A tag cria hiperlinks; href="#servicos" determina a referência que ira te levar para o elemento marcado com #.

## Aula 5

Dentro da tag <*a*> podemos inserir links formatados da seguinte forma, <*a href="url_do_site" target="_blank"*>, target="_blank" abri o link externo ou interno em uma nova aba e sem a necessidade de sair da aba atual;

Ex HTML5: <*a href="https://www.google.com/" target="_blank"></a*>

# CSS 3

* CSS é o acrônimo de Cascade Style Sheet (Folhas de estilo em cascata);

## Aula 1

* Criando o documento CSS, ele utiliza o padrão .css, sendo assim, o documento terá o nome style.css;
* Devemos fazer referência ao nosso documento css dentro do documento html, <*link rel="stylesheet" type="text/css" href="css/style.css"*>;
* Dentro do documento css devemos definir parâmetros para o documento html;

**Cores podem adicionadas usando padrão hexadecimal, nome ou escala rgb** ;

Padrão para formatação de estilos consiste no uso de Elemento {formatações}:

Ex CSS3: *h1 {color: red} - todo título com h1 será escrito com a fonte na cor vermelha(red)*;

## Aula 2

Podemos atribuir formatações para todos os elementos do documento html, h1..., body, footer, img, etc. Podemos utilizar # para declarar um ID e . para classe.

Ex HTML5: <*img src="img/parceiro2.jpg" width="150px" class="img_padrao"*>;

Ex CSS3: *.img_padrao {margin: 20px}*