# HTML5

É uma linguagem de marcação que tem as seguintes responsabilidades:

- Conteúdo;
- Semântico (tags);

- `<h1>` - heading 1 - 6
Usamos ele quando queremos definir títulos.

- `<a>` - Link (a- anchor)
Usamos ela para definir a navegação do usuário. Se você tem um texto que você quer que o usuário clique e ele vá para outro lugar você pode usar essa tag junto com o atributo `href`. Exemplo de um `a` que o usuário é direcionado para o site da collabcode.training:

```
<a href="http://collabcode.training">CollabCode.Training</a>
```

- `header` é onde colocamos o cabeçalho do site. Nesse cabeçalho pode conter tesxto, imagens ou menu.

```
    <header>
        <h1>LOGO</h1>
        
            <a href="#">Produtos</a>
            <a href="#">Serviços</a>
            <a href="#">Sobre</a>
        
    </header>
```

- `nav` (navigation) é usado para englobar um menu de navegação.

```
    <nav>
        <a href="#">Produtos</a>
        <a href="#">Serviços</a>
        <a href="#">Sobre</a>
    </nav>
```

# CSS

É uma linguagem de estilo, isso que dizer que ela tem as seguintes responsabilidades: 

- Visual;

O  código **CSS** pode ficar tanto dentro no nosso código **HTML**, como em um arquivo separado. O ideal é que seja utilizado em um arquivo separado. 

Criando o arquivo **CSS**:

1. crie uma arquivo com a extensão CSS
```
nomeDoArquivo.css
```
2. dentro do arquivo **HTML** na tag `head` coloque o seguinte link:2 

```
<link rel="stylesheet" href="nomeDoArquivo.css">
```

No arquivo CSS são definidas todas as propriedades que serão aplicadas as tags do HTML. Essas propriedades devem ficar entre chaves '{ }'.

```
body{
    background-color: #e24647; /* a propriedade vai altera a cor de fundo da página.*/
}
```

`color`- essa propriedade altera a cor da letra.

```
body{
    color:#fff; /* a cor da letra ficará branca*/
}
```

`text-decoration` quando usado com o atributo `none` retira o sublinhado dos link.

`font-size` define o tamanho da fonte.

`inherit` (herdar) defini o atributo da tag que estiver sendo usado igual ao do pai.

`font-family` define a família da fonte.

