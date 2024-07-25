``` mermaid
---
title: Animal example
---
classDiagram
    note "From Duck till Zebra"
    Animal <|-- Canard
    note .. Canard
    note for Duck "can fly\ncan swim\ncan dive\ncan help in debugging"
    Animal <|-- Poisson
    Animal <|-- Lion
    Animal <|-- Zebre
    Animal : +int age
    Animal : +String gender
    Animal: +isMammal()
    Animal: +mate()
    class Canard{
        +String beakColor
        +swim()
        +quack()
    }
    class Poisson{
        -int sizeInFeet
        -canEat()
    }
    class Zebre{
        +bool is_wild
        +run()
    }
    class Lion {
        +strong()
        +run()
    }


```
