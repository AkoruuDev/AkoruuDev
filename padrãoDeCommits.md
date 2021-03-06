# Padrão de commits

Embora a área de commits seja livre para digitar como desejar, é importante sempre pensar em como facilitar esses comentários para outras pessoas verem
Isso se torna ainda mais importante quando se trata de projetos que envolvam mais de um DEV no mesmo projeto

### Abaixo será mostrado um padrão de commits que podem ser seguidos por quem desejar a fim de facilitar a visualização dos commits por outros Devs

<img alt="Bas Git" src="src/images/padrão de commits/Bas Git.png"/>

A parte <strong>git commit -m</strong> já é padrão para o lançamento de commits via terminal e tudo aquilo que está depois entre " " será organizado com o padrão apresentado aqui neste arquivo

<strong>TIPO - </strong>Nesta área é dita qual é o tipo de commit que está sendo feita;
Já existe alguns TIPOS pré existentes e, logo aqui em baixo, será apresentado alguns modelos pra começar;
Lembre-se sempre que, para o TIPO, é importante coloca-lo em LETRAS CAIXA (Letras maiusculas);
É importante ressaltar que se houver mais de uma área editada, o TIPO é dado para a área de maior importância, ou seja, se houver edição no arquivo HTML e também no arquivo JavaScript, o DEV será responsável por verificar qual dos arquivos teve a edição mais relevante para escolher o melhor TIPO

<strong>Escopo - </strong>O setor de Escopo é descrito dentro de colchetes [ ] e com a primeira letra em maiuscula;
O escopo é como o título do comentário, é como uma breve descrição do que foi mudado;
É importante ressaltar que se houver mais de uma área editada, o Escopo é dado para a área de maior importância, ou seja, se houver edição em mais de uma função no arquivo JavaScript, o DEV será responsável por verificar qual das funções teve a edição mais relevante para escolher o melhor Escopo

<strong>GitHubDev - </strong>O setor de GitHubDev é descrito dentro de parênteses ( ) e deve ser seguido de acordo com o nome do dev no GitHub;
Esta área é usada exclusivamente quando o projeto em questão é desenvolvida por mais de um Dev e, sendo assim, dentro dos parênteses ( ) é colocado o nome do Dev que fez o commit seguindo o padrão do nome do GitHub

<strong>Descrição da commitagem - </strong>logo depois dos dois pontos : é descrito todas as edições que foram feitas dentro daquele commit sendo separadas por ponto e virgula ; de edição para edição;
É interessante dizer que, nesta área, toda a descrição deve ser feita no infinitivo (final ar, er, ir);
Lembre-se sempre de colocar a descrilção de todas as edilções que foram feitas

# TIPOS
### Abaixo será mostrado todos os TIPOS relevantes por enquanto e para que cada um serve

#### FIX
<img alt="FIX" height="150px" src="src/images/padrão de commits/FIX.png"/>
Geralmente usado para edições mínimas de correção de bugs ou áreas que devem ser ajustadas

#### FEAT 
<img alt="FEAT" height="150px" src="src/images/padrão de commits/FEAT.png"/>
Geralmente usado para edição em arquivos .js ou similares

Caso a implementação não esteja 100% concluida, utilize o TIPO CHORE logo abaixo

#### CHORE
<img alt="CHORE" height="150px" src="src/images/padrão de commits/CHORE.png"/>
Geralmente usado quando se inicia uma implementação, mas ainda não está completa, por faltar algum detalhe ou por ter tido que parar no meio da edição por razões maiores

#### BAS
<img alt="BAS" height="150px" src="src/images/padrão de commits/BAS.png"/>
Geralmente usado para edição em arquivos .html ou similares

#### STYLE
<img alt="STYLE" height="150px" src="src/images/padrão de commits/STYLE.png"/>
Geralmente usado para edição em arquivos .css ou similares

#### REFACTOR
<img alt="REFACTOR" height="150px" src="src/images/padrão de commits/REFACTOR.png"/>
Geralmente usado quando se edita a organização do código, adiciona comentários entre linhas e/ou mantém a estrutura das linhas como estava abtes

#### DOCS
<img alt="DOCS" height="150px" src="src/images/padrão de commits/DOCS.png"/>
Geralmente usada quando se cria ou atualiza arquivos de documentação, geralmente imagens ou arquivos de informações .txt ou similares

#### RES
<img alt="RES" height="150px" src="src/images/padrão de commits/RES.png"/>
Usado APENAS quando se trata de edições feitas para implementação de responsividade desktop/mobile ou similares

#### CORF
<img alt="CORF" height="150px" src="src/images/padrão de commits/CORF.png"/>
Geralmente usado em projetos que se utilizam de mais de um DEV
Commit feito logo depois do Pull quando há a necessidade de escolha de versões

### Abaixo será demonstrado alguns exemplos de commits utilizando o padrão explicado acima

<img alt="Exp Git" src="src/images/padrão de commits/Exp Git.png"/>

Como pode ver acima, há 3 (três) exemplos de commits utilizando o mesmo padrão;

O primeiro se trata de um Commit feito com a edição do tipo STYLE na área de Login e, logo depois do nome do DEV que fez o comentário, há a descrição detalhada do commit

O segundo trata-se de um commit feito com a edição do tipo DOCS relacionado ao arquivo README.md. Este commit, diferente do primeiro, não há a área de GitHuvDev, o que quer dizer que, para este projeto, existe apenas a eddição de um único DEV, que também é o dono do repositório. Na descrição detalhada, mostra que, o que foi feito, foi a criação do arquivo

Já o terceito, também feito pelo usuário dono do repositório, também é do tipo DOCS e de escopo sobre a Database. Nele, diferente dos outros, há vários itens de edição, todos feitos no infinitivo (final ar, er, ir) e separados por ponto e virgula ; como instruído acima;