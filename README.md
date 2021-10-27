# Notas - Discover Rocketseat

## 📌 Preparação de astronautas
### CSS
<details>
<summary>Uma caixa dentro da outra</summary>

  - **Box Sizing**
    - No CSS seguimos um _Box model_ (modelo de caixa).
    - O _Box Sizing_ (Tamanho da caixa), por padrão, é _Box content_ (Conteúdo da caixa), ou seja, tamanho em relação ao conteúdo.
    - O _Border-box_ (Caixa pela borda), torna o tamanho da caixa medido pela borda e não mais pelo conteúdo.
  
  - **Display-block-inline**
    - display-block: por padrão a maioria dos elementos.
      - Elementos um abaixo do outro
      - Width e height são respeitados
      - Padding, margin, border funcionam normalmente
    - display-inline: em linha (elemento de \<strong>, \<span>, \<a> e \<em>)
      - Elementos um ao lado do outro
      - Width e height NÃO são respeitados
      - Padding, margin, border funcionam somente na horizontal
  
  - **Margin**
    - propriedades: margin-top, margin-right, margin-bottom, margin-left
    - valores: length, percentagem, auto
    - auto: por padão ajusta marens laterais
    - margin collapys: quando a margin bottom sobrepõe o margin top
    - shorthand (agrupamento):
      - maring: 12px(top) 12px(right) 0(bottom) 12px(left);
      - margin: 12px(top) 10px(right-left) 0(bottom);
      - margin: 8px(top-bottom) 10px(right-left);
      - margin: 10px(todos lados)
  
  - **Padding**
    - propriedades: padding-top, padding-right, padding-bottom, padding-left
    - valores: length, percentagem
    - padding e a caixa: o padding pode aumentar o tamanho da caixa. (por padrão, box content)
    - shorthand (agrupamento):
      - padding: 12px(top) 12px(right) 0(bottom) 12px(left);
      - padding: 12px(top) 10px(right-left) 0(bottom);
      - padding: 8px(top-bottom) 10px(right-left);
      - padding: 10px(todos lados)
  
  - **Border e outline**
    - valores:
      - border-style: solid | dotted | dashed | double | groove | ridge | inset | outset
      - border-width: length
      - border-color: cor
    - shorthand:
      - direção
        - border-top: solid 2px;
      - style
        - border: solid;
      - width | style
        - border: 2px dotted
      - style | color
        - border: outset #f33
      - width | style | color
        - border: medium dached green
    - Outline: diferença
      - Não modifica o tamanho da caixa, pois não é parte do Box Model;
      - Não permite ajuste individual
      - Mais usado para acessibilidade
  
</details>


<details>
<summary>Posicionando foguetes</summary>

  - **Layouts** (história)
    - tablets
    - floats e clear
    - frameworks e grid systems
    - flexbox
    - grid
  
   - **Position**
    - Static (por padrão, seguindo o fluxo da página)
    - Relatice (elemento fica no lugar relativo a posição designada e tem o fluxo normal do scrool)
      - propriedades: top | right | bottom | left | z-index
    - Absolute (como se subisse uma camada, sendo absoluto em relação a página, mas se tiver um elemento pai relativo, ele será absosulto em relação a ele)
      - propriedades: top | right | bottom | left | z-index
    - fixed (o elemento fica fixo na pagina)
    - Element Staking
      - z-index: subindo uma camada
  
  - **Flexbox**
    - posicionamento | alinhamento | direcionamento | ordernação | tamanhos | dimensão
    - direcionamento: flex-direction -  direção do flex (horizontal-row | vertical-column)
    - alinhamento: justify-content(column) | align-itens(row)
  
  - **Grid**
    - posicionamento dos elementos dentro da caixa, igual o flexbox e diferente de block e inline
    - horizontal e vertical
    - flexível ou fico
    - cria espaços para os elementos filhos habitarem
    - propriedades:
      - grid-template-areas: areas no grid, quantas colunas e linhas (dinâmico)
      - grid-template-columns: tamanhos das colunas (fr = fração restante)
      - grid-template-rows: tamanho das linhas (fr = fração restante)
    - pode ser utilizado em conjunto com flexbox
  
</details>

<details>
<summary>Alinhando os planetas</summary>

  - Terminologia:
    - container:
    - nesting:
    -
  
</details>
