---
author: "Daniel Caballo"
title: "Como se hace un Grafico"
description: "No Funciona en este Web"
tags: ["markdown", "css", "html"]
date: 2022-10-22
thumbnail: https://media.giphy.com/media/h7uQzyT755jVibc0fj/giphy.gif
math: true
---


<p>
<span class="nowrap"><span class="emojify">🙉</span>
<span class="nowrap"><span class="emojify">🙉</span>

**Antes de hacerlo cuidado lee esto anda**  <br>
https://peterlavalle.github.io/post/gohugo-mermaid/

<span class="nowrap"><span class="emojify">🙉</span>
<span class="nowrap"><span class="emojify">🙉</span>
</p>

**Diagram Types**

{{<mermaid align="left">}}
graph LR;
    A[Hard edge] -->|Link text| B(Round edge)
    B --> C{Decision}
    C -->|One| D[Result one]
    C -->|Two| E[Result two]
{{< /mermaid >}}

**Sequence diagram**

{{<mermaid>}}
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail...
    John-->Alice: Great!
    John->Bob: How about you?
    Bob-->John: Jolly good!
{{< /mermaid >}}

**Gantt diagram**

{{<mermaid align="left">}}
gantt
    dateFormat  YYYY-MM-DD
    title Adding GANTT diagram functionality to mermaid
    section A section
    Completed task            :done,    des1, 2014-01-06,2014-01-08
    Active task               :active,  des2, 2014-01-09, 3d
    Future task               :         des3, after des2, 5d
    Future task2               :         des4, after des3, 5d
    section Critical tasks
    Completed task in the critical line :crit, done, 2014-01-06,24h
    Implement parser and jison          :crit, done, after des1, 2d
    Create tests for parser             :crit, active, 3d
    Future task in critical line        :crit, 5d
    Create tests for renderer           :2d
    Add to mermaid                      :1d
{{< /mermaid >}}

**Class diagram**

{{<mermaid align="left">}}
classDiagram
Class01 <|-- AveryLongClass : Cool
Class03 *-- Class04
Class05 o-- Class06
Class07 .. Class08
Class09 --> C2 : Where am i?
Class09 --* C3
Class09 --|> Class07
Class07 : equals()
Class07 : Object[] elementData
Class01 : size()
Class01 : int chimp
Class01 : int gorilla
Class08 <--> C2: Cool label
Class diagram
{{< /mermaid >}}

**Git graph**

{{<mermaid align="left">}}
   gitGraph:
options
{
    "nodeSpacing": 64,
    "nodeRadius": 8
}
end
    commit
    branch newbranch
    checkout newbranch
    commit
    commit
    checkout master
    commit
    commit
    merge newbranch
{{< /mermaid >}}

**Cositas que si funcionan**

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

Press <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> to end the session.

Most <mark>salamanders</mark> are nocturnal, and hunt for insects, worms, and other small creatures.

Block math:

$$
 \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } }
$$

**Note:** Puedes usar mas  [Supported TeX Functions](https://katex.org/docs/supported.html)

**Tambien Se pueden hacer tablas**

Crear tablas :

|Tabla|Tabla1|Tabla2|
|-----|------|-----|
|Valor1|Valor2|Valor3|
|Valor1|Valor2|Valor3|
|Valor1|Valor2|Valor3|
|Valor1|Valor2|Valor3|
