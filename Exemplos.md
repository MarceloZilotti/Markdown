

# H1
## H2
### H3
#### H4
##### H5
###### H6

*Itálico* ou _Itálico_  
**Negrito** ou __Negrito__  
***Negrito e Itálico*** ou ___Negrito e Itálico___  
~~Texto Riscado~~  

---
- Item 1
- Item 2
  - Subitem (2 espaços ou Tab)
---

  Algumas palavras <ins>serão sublinhadas</ins>.

---

1. Primeiro item
2. Segundo item

---
- [ ] Tarefa pendente  
- [x] Tarefa concluída  

---

[![Google logo](https://www.google.com.br/images/branding/googlelogo/2x/googlelogo_color_272x92dp.png)](https://www.google.com.br/)
---
Mostrar código:

```python
def hello_world():
    print("Hello, World!")
```
---
> :warning: **Warning:** Do not push the big red button.

> :memo: **Note:** Sunrises are beautiful.

> :bulb: **Tip:** Remember to appreciate the little things in life.
---

> Isto é uma citação.  
> **Autor Desconhecido**




---
***
___



| Nome    | Idade | Profissão   |
|---------|-------|-------------|
| João    | 30    | Engenheiro  |
| Maria   | 25    | Design      |



Para gerar tabelas automaticamente em Markdown, pode-se usar: [Tables Generator](https://www.tablesgenerator.com/markdown_tables)

| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| Paragraph   | First paragraph. <br><br> Second paragraph. |


| Syntax      | Description |
| ----------- | ----------- |
| Header      | Title |
| List        | Here's a list! <ul><li>Item one.</li><li>Item two.</li></ul> |

| ![Chrome Image](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fau2ph8juz4l6gu8m6v99.png) | ![Firefox Image](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Fwnv0yb558uyvttyxnsz7.png) | ![Edge Image](https://media2.dev.to/dynamic/image/width=800%2Cheight=%2Cfit=scale-down%2Cgravity=auto%2Cformat=auto/https%3A%2F%2Fdev-to-uploads.s3.amazonaws.com%2Fuploads%2Farticles%2Foc95bmrx1ic1yv2ufxnp.png) |
|---------|-------|-------------|
| 1       | 2     | 3           |


### VIDEO:

[![This is a Video](https://th.bing.com/th/id/OIP.CCk-bwcVjwZMs_ANGVFsAgHaE8?w=276&h=184&c=7&r=0&o=5&dpr=1.5&pid=1.7)](https://www.youtube.com/watch?v=bwNDSAuDACc)
---


Texto com uma nota[^1].  
[^1]: Explicação da nota.  


:rocket: :brazil: :smile:  

---

<!-- Este é um comentário que não será exibido
|Here’s a partial list of HTML entities for symbols|
-----

|Copyright (©) — &copy;|
---
|Registered trademark (®) — &reg;|
---
|Trademark (™) — &trade;|
---
|Euro (€) — &euro;|
---
|Left arrow (←) — &larr;|
---
|Up arrow (↑) — &uarr;|
---
|Right arrow (→) — &rarr;|
---
|Down arrow (↓) — &darr;|
---
|Degree (°) — &#176;|
---
|Pi (π) — &#960;|
---
 -->

<figure>
    <img src="https://mdg.imgix.net/assets/images/albuquerque.jpg?auto=format&fit=clip&q=40&w=1080"
         alt="Albuquerque, New Mexico">
    <figcaption>A single track trail outside of Albuquerque, New Mexico.</figcaption>
</figure>

```diff
+ Texto adicionado  
- Texto removido  
```

```mermaid
sequenceDiagram
Alice ->> Bob: Hello Bob, how are you?
Bob-->>John: How about you John?
Bob--x Alice: I am good thanks!
Bob-x John: I am good thanks!
Note right of John: Bob thinks a long<br/>long time, so long<br/>that the text does<br/>not fit on a row.

Bob-->Alice: Checking with John...
Alice->John: Yes... John, how are you?
```

And this will produce a flow chart:

```mermaid
graph LR
A[Square Rect] -- Link text --> B((Circle))
A --> C(Round Rect)
B --> D{Rhombus}
C --> D

```
-----



``` mermaid
flowchart LR
    id1(Box with round corner)
    id2([Stadium])
    id3[(Database)]
    id4((Circle))
    id5{{Hex}}
    id6[\Parallelogram\]
    id7[\Trapezoid/]

    id1-- 1st line ---id2
    id1--> |2nd line| id3
    id1--- |3rd line| id4
    id2-.-|4th line| id5
    id3 == 5th line ==> id6
    id4 <--> id7 --> id6

    style id1 fill:green,stroke:black
    style id2 fill:white,stroke:#f66,stroke-dasharray: 5, 5,color:black
    style id3 fill:#66f,stroke:#f6f,stroke-width:4px
    style id4 fill:red,stroke:yellow
    style id5 fill:orange,stroke:white,color:black
    style id6 fill:yellow,stroke:blue,color:black
    style id7 fill:brown,stroke:blue
```
