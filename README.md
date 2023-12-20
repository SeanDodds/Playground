# Playground
This is my github play ground. 
```mermaid
sequenceDiagram
    actor QA
    participant github
    participant jenkins
    participant argocd
```

``` mermaid
    gitGraph 
       commit id: "JIRA-1001"
       commit id: "JIRA-1002"
       commit id: "JIRA-1003" tag: "Build #123, L1"
     
```
```mermaid
---
title: Order example
---
erDiagram
    CUSTOMER ||--o{ ORDER : places
    ORDER ||--|{ LINE-ITEM : contains
    CUSTOMER }|..|{ DELIVERY-ADDRESS : uses
```


```mermaid
requirementDiagram

    requirement test_req {
    id: 1
    text: the test text.
    risk: high
    verifymethod: test
    }

    element test_entity {
    type: simulation
    }

    test_entity - satisfies -> test_req
```
