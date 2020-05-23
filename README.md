# Responsividade

## CSS Units

Unidades de medidas do css

Layout Fixo
`px` - Pixels

Layout Fluid
`%`
`auto`
`vh`
`vw`

Textos fixos
`px`
`pt`

Textos fluidos

`em` - mutiplicado pelo pai
`rem` - multiplicado pelo root

## Media Queries

```css
@media(max-width: 320px){
  #form h3{
    font-size: 2.4rem;
}
```

## HTML Media Queries

```
    <link rel="stylesheet" href="print.css" media="print" >
```

## Image
- Manipulção para tornar a imagem fluida no (cards)
    ``` Codigo
        .image{
        width: 100%;
        padding-top: 56.25%;
        overflow: hidden;
        position: reative;
        }
        .img-fluid{
        width: 100%;
        position:absolute;
        top:50%;
        left: 50%;
        transform: translate(-50%, -50%);
        }
    ```

`<picture>`

JPG, PNG vs SVG