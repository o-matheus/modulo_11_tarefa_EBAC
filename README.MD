# Tarefa Módulo 11
A entrega deste exercício consiste em:

- Criar um layout responsivo de uma loja virtual;
- Criar uma seção “Sobre a Loja”, onde haverão duas colunas: uma com a imagem da loja e outra com um texto;
- Criar uma seção de produtos contendo uma listagem de quatro produtos, dispostos lado a lado, com imagem, nome, descrição do produto e um botão para adicionar ao carrinho;
- Seguir as adaptações de layout propostas e publicar na Vercel, enviando o link do projeto.

## Menu
- [Layout](#layout)
- [Ferramentas Utilizadas](#ferramentas-utilizadas)
- [Desafios](#desafios)
- [Considerações Finais](#considerações-finais)

## Layout
![Layout](Readme/Imagens/Wood%20Studio.jpg)

## Ferramentas Utilizadas
[Visily](https://www.visily.ai/)  
Utilizei essa ferramenta em vez do Figma, pois achei mais fácil manipular as informações. Além disso, existem muitos modelos, cards e containers de sites de referência que podemos editar.  
[Canva](https://www.canva.com/pt_br/)  
Usei para criar a logo e o favicon do site.  
[Remove.bg](https://www.remove.bg/)  
Ferramenta utilizada para remover o fundo das imagens.  
[LunaPic](https://www1.lunapic.com/editor/)  
Editor online usado para cortar a logo e deixar apenas a imagem desejada, sem espaço em branco.

## Desafios
### Favicon
O primeiro desafio foi criar o favicon. Inicialmente, fiz ele muito pequeno no Canva, e quando fui utilizá-lo, ficou ilegível. Para corrigir esse problema, voltei ao Canva e aumentei a imagem até ocupar todo o espaço disponível. Depois disso, o resultado foi satisfatório.

### Logo
Remover o fundo branco da logo estava atrapalhando na organização do elemento via CSS. Resolvi isso com o Remove.bg e o LunaPic.

### Menu Responsivo
Passei bastante tempo ajustando o menu na versão mobile para que ele ficasse visualmente mais agradável. O problema era que os itens do menu estavam abaixo do logo e ultrapassavam seu tamanho, dando a impressão de desalinhamento, mesmo estando aparentemente alinhados. Quando descobri isso, consegui corrigir o problema.

### CSS
Durante a criação dos `@media`, adicionei um ponto e vírgula (`;`) no final da regra, o que causou a interrupção da leitura do código. Demorei algum tempo para entender o erro. Em algum momento desse processo, fiz uma alteração que desconfigurou todo o layout, então precisei utilizar `Ctrl + Z` até voltar ao estado correto. 

## Considerações Finais
Diferente do projeto da lista de tarefas, iniciei este já com o design da landing page completo, incluindo logo e favicon! Fiquei feliz com o resultado, mas foi um processo demorado, levando aproximadamente **1h30**.

A principio, achei que o favicon tinha ficado bom, mas percebi que estava pequeno demais. Tive que refazer para obter um resultado adequado. 

Fiz algumas alterações no design e acabei removendo a seção do formulário de encomendas. Passei bastante tempo desenvolvendo este projeto e decidi focar apenas no que foi solicitado. Acredito que, no futuro, quando puder integrar funcionalidades no backend, revisitarei essa parte e aplicarei minhas anotações sobre a validação com plugins do jQuery.

Durante o processo, senti que minha linha de raciocínio e as pesquisas iniciais no ChatGPT me levaram a escrever códigos mais extensos do que o necessário. Preciso me aprofundar mais na otimização do código.

No CSS, utilizei `max-height: fit-content;` em algumas partes, o que acabou alterando um pouco o layout. No entanto, gostei do resultado. Tentei usar variáveis flexíveis, mas ainda não sei se implementei da maneira mais recomendada.

Lendo meu próprio código HTML e CSS, consigo interpretar tudo, mas algumas partes como **grid** e algumas soluções que usei no `@media` ainda não estão fixadas na minha mente. No geral, fiquei satisfeito com a experiência e com o aprendizado adquirido!