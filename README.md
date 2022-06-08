aprendendo markdown
<!-- cabeçalho -->
# cabeçalho 1 
## cabeçalho 2 
### cabeçalho 3 
#### cabeçalho 4 
##### cabeçalho 5 
###### cabeçalho 6 

<!-- italico -->
\*palavra\* em italico  
_palavra_ em italico

<!-- dobre e será strong -->
\*\*palavra\*\* em strong 
__palavra__ em strong

<!-- linha no meio -->
\~\~palavra\~\~ perfurada  

~~palavra~~ perfurada

<!-- link -->
> $[travesso](https://www.travesso.com "travesso...") 
### pt-br
> [**Guia de Markdown**][2] [~~wiki do markdown~~][1]
### en
>[~~Markdown-wiki~~][1]. [**Markdown-guide**][2] 

[1]: http://en.wikipedia.org/wiki/Markdown  "Markdow"
[2]: https://markdown-guide.readthedocs.io "markdown-guide"


<!-- ul -->
* item 1
* item 2
* item 3
  * valor 1
  * valor 2

<!-- ol -->
1. item
2. item
3. item

<!-- inline code block -->
`<p>um bloco de codigo em linha(paragrafo)</p>`

<!-- imagem -->
![logo Markdown](https://markdown-here.com/img/icon256.png "logo Mark")
---
> ## BASH
```bash
npm install sass
npm run start
```

> ## SASS

```scss
body{font-family: courier;}

@mixin h1-header{
  font-size: 2.5rem;
  font-weight: bold;
  text-align: center;
}

h1{
  @include h1-header
}
```

```scss
// _library.scss
$black: #000 !default;
$border-radius: 0.25rem !default;
$box-shadow: 0 0.5rem 1rem rgba($black, 0.15) !default;

code {
  border-radius: $border-radius;
  box-shadow: $box-shadow;
}

// style.scss
@use 'library' with (
  $black: #222,
  $border-radius: 0.1rem
);

```

<!-- table -->
| Name      |Email|
|-----------|----------|
|john long  |jonh@mail.com|
|young jong |young@mail.com|

<!-- lista de tarefas -->
* [x] fazer 1
* [x] fazer 2
* [ ] fazer 3
* [ ] fazer 4
* * * item 01

+ um
- dois
* tres

---
texto
====
texto2
===
## textando o revert --no-edit
#### para ver se fuciona
##### bla bla bla
