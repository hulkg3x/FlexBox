# FlexBox
Curso Flexbox: Posicione elementos na tela : https://cursos.alura.com.br/course/posicione-elementos-com-flexbox

<p align="center">
  <img src="https://cdn-images-1.medium.com/max/1366/1*HFAEJvVOq4AwFuBivNu_OQ.png" width="800">
</p>

# FlexBox

> O flexbox é mais uma nova propriedade do CSS, que ajuda alinhar posicionar elementos no nosso site de uma forma mais facil.

- Para iniciar um flexbox e usar todas suas propriedades usamos a propriedade ```display```.
- Exemplo :

```css
  div {
    display: flex;
  }
```
- Ao usar o elemento ```flex```, o conteudo fica lado a lado.

> Para espaçar conteudo entre si usamos :

```css
  div {
    display: flex;
    justify-content: space-between;
  }
```

<p align="center">
<img src="https://s3.amazonaws.com/caelum-online-public/1_flexbox/5_2+mostrando+os+itens+distribu%C3%ADdos.png" width="500">

- com o ```justify-content: space-between;``` os conteudo espaça entre si.

> Para espaçar em torno dos elementos usamos :

```css
  div {
    display: flex;
    justify-content: space-around;
  }
```
<p align="center">
<img src="https://s3.amazonaws.com/caelum-online-public/1_flexbox/5_4+mostrando+os+itens+distribu%C3%ADdos.png" width="500">

- com o ```justify-content: space-around;``` os conteudo espaça em torno de si.

> Para Centralizar os elementos usamos :

```css
  div {
    ...
    align-items: center;
  }
```

> Temos as direçoes que desejamos por no nosso elemento. Seria:

```css
  div {
    ...
    flex-direction: column;
  }

  ou...

  div {
    ...
    flex-direction: row;
  }
```

- ```column``` faz com que o elemento seja em colunas.
- ```row``` faz com que o elemento seja em linhas.

> Dependendo da direção do elemento, o ```justify-content``` funciona de forma diferente. 

- Exemplo em ```coluna``` , ja que o de ```linha``` vimos acima exemplos.

```css
div {
    display: flex;
    /*justify-content: space-around;
    align-items: center;*/
    flex-direction: column;
}
```

<p align="center">
<img src="https://s3.amazonaws.com/caelum-online-public/1_flexbox/5_5+mostrando+a+distribui%C3%A7%C3%A3o+dos+itens.png" width="400">

- os elementos estao em colunas.
- Usando o ```align-items: center;```.

```css
div {
    display: flex;
    /*justify-content: space-around;
    align-items: center;*/
    align-items: center;
    flex-direction: column;
}
```
<p align="center">
<img src="https://s3.amazonaws.com/caelum-online-public/1_flexbox/5_6+mostrando+os+itens.png" width="500">

- E podemos espaçar esses elementos entre si.
>Lembrando que depende do container onde esses elementos estão, eles so irá espaçar se tiver espaço dentro do container.

- Por exemplo:

```
- se o container tiver 1000px, e suas 5 divs dentro do container ocupar cada um 100px, voce irá de fato espaçar entre as 5. 200px para cada. Caso tiver 500px no container. De fato nao irá conseguir espaçar os elementos entre si.
```