<h1 align="center">
    <img alt="Launchbase - Rocketseat" src="https://storage.googleapis.com/golden-wind/bootcamp-launchbase/logo.png" width="300px" />
</h1>

<h3 align="center">
  Desafio 2-1: Primeiro HTML
</h3>

### :rocket: Sobre o desafio
Criar um arquivo html que contenha um favicon e um header com 3 links: Comunidade, Email e Telefone.

### :sunglasses: Estilização

Você tem liberdade para escolher a estilização que preferir para esse desafio, mas alguns pontos são obrigatórios:

:white_check_mark: Deve ser aplicado um background

:white_check_mark: Deve ser utilizada a fonte Roboto

:white_check_mark: O header precisa ocupar todo o espaço lateral e superior (body sem margin)

:white_check_mark: O header precisa ter um espaçamento interno de 30px em todas as direções

:white_check_mark: Os links devem ter um espaçamento de 30px entre si


<h3 align="center">
  Desafio 2-2: Página de descrição
</h3>

### :rocket: Sobre o desafio
A partir do arquivo do desafio 2-1, adicionar um novo link no header chamado Sobre. Essa página deverá mostrar informações referentes a Rocketseat.

### Informações da página
:white_check_mark: Uma imagem da logo da empresa

:white_check_mark: O nome da empresa

:white_check_mark: Uma breve descrição da empresa

:white_check_mark: Uma lista com as principais tecnologias utilizadas. Dica: utilize a tag `ul` para lista e `li` para o item da lista.

:white_check_mark: Links para as redes sociais da empresa (Github, Instagram e Facebook)

### :sunglasses: Estilização
Você tem liberdade para escolher a estilização que preferir para esse desafio, mas alguns pontos são obrigatórios:

:white_check_mark: A imagem deve ter uma borda e um formato circular.

:white_check_mark: Deve ser utilizada a fonte Roboto

:white_check_mark: O nome da empresa e a imagem devem ser destacar do restante

:white_check_mark: Os links das redes sociais devem ter alguma alteração visual quando o cursor do mouse passar por cima

<h3 align="center">
  Desafio 2-3: Página de posts e iframe 
</h3>

### :rocket: Sobre o desafio
A partir do arquivo do desafio 2.2, adicionar no header um link chamado Conteúdos. Essa página deve conter um grid onde devem ser mostrados os seus 3 posts favoritos do Blog da Rocketseat. Ao clicar em um dos posts, deve ser aberta uma modal onde um iframe irá carregar as informações do post selecionado.

### Informações da página

:white_check_mark: Título da página

:white_check_mark: Grid com 3 colunas e 1 linha onde serão apresentados os cards dos posts

### Informações do card

- Imagem de destaque do Post (Tutorial de como pegar os links das imagens)
- Título do Post
- Autor do Post
- Tempo de Leitura

### Modal

O modal deve conter um iframe que busca a página do post (dica: basta adicionar o Slug - versão padronizada do título - ao final de https://blog.rocketseat.com.br/, por exemplo, axios-um-cliente-http-full-stack). Além do botão de fechar o modal, é preciso implementar a funcionalidade de maximizar o modal (dica: utilize a mesma lógica implementada para fechar o modalOverlay, mas trabalhe com a classe modal e utilize o método contains do classList para verificar se o elemento está ou não com a classe maximize).

### :sunglasses: Estilização

Você tem liberdade para escolher a estilização que preferir para esse desafio, mas alguns pontos são obrigatórios:

- Deve ser utilizado o grid para organizar os posts
- O modal nunca deve abrir maximizado

<p align="center">
  Feito com :purple_heart: por Thaísa Elvas :)
</p>