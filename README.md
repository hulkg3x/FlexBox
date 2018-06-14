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