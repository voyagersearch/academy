.. meta::
   :title: ISO 19115 Metadata Record | Lineage Requirements
   :description: Provides information on fields required to support metadata lineage.. 
   :keywords: 19115, ISO-19115, data governance, data provenance, data profiling, data lineage

Voyager Search Academy
===================================

19115
------

Lineage
-------

This diagram provides information on the metadata fields and codes for lineage

```mermaid
flowchart TD;
    A[Start] --> B[Process 1];
    B --> C[Process 2];
    C --> D[End];
```



```mermaid
classDiagram
    class Animal {
        +name: string
        +age: int
        +makeSound(): void
    }

    class Dog {
        +breed: string
        +bark(): void
    }

    class Cat {
        +color: string
        +meow(): void
    }

    Animal <|-- Dog
    Animal <|-- Cat
```

%%The below line of code will open the file that is in the current folder with the same name

```mermaid
classDiagram
    class Animal {
        +name: string
        +age: int
        +makeSound(): void
    }

    class Dog {
        +breed: string
        +bark(): void
    }

    class Cat {
        +color: string
        +meow(): void
    }

    Animal <|-- Dog
    Animal <|-- Cat
```
