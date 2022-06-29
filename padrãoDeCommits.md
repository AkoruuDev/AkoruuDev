# Padrão de commits

Embora a área de commits seja livre para digitar como desejar, é importante sempre pensar em como facilitar esses comentários para outras pessoas verem
Isso se torna ainda mais importante quando se trata de projetos que envolvam mais de um DEV no mesmo projeto

### Abaixo será mostrado um padrão de commits que podem ser seguidos por quem desejar a fim de facilitar a visualização dos commits por outros Devs

<img alt="FIX" src="src/images/padrão de commits/Bas Git.png"/>

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