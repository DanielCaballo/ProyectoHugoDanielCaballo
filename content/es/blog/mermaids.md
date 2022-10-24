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
<span class="nowrap"><span class="emojify">🙉</span>
<span class="nowrap"><span class="emojify">🙉</span>
</p>

**Diagram Types**
```mermaid
Flowchart
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
**Sequence diagram**

sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail!
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
Sequence diagram

**Gantt diagram**

gantt
dateFormat  YYYY-MM-DD
title Adding GANTT diagram to mermaid
excludes weekdays 2014-01-10

section A section
Completed task            :done,    des1, 2014-01-06,2014-01-08
Active task               :active,  des2, 2014-01-09, 3d
Future task               :         des3, after des2, 5d
Future task2               :         des4, after des3, 5d
Gantt diagram

**Class diagram**

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

**Git graph**

    gitGraph
       commit
       commit
       branch develop
       commit
       commit
       commit
       checkout main
       commit
       commit
main
develop
0-5c8a78f
1-c00e363
2-6f8b206
3-3b263c5
4-ec740ba
5-4583eb1
6-90b66b6

**Entity Relationship Diagram - exclamation experimental**

erDiagram
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses

ER diagram

**User Journey Diagram**

journey
    title My working day
    section Go to work
      Make tea: 5: Me
      Go upstairs: 3: Me
      Do work: 1: Me, Cat
    section Go home
      Go downstairs: 5: Me
      Sit down: 5: Me

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
