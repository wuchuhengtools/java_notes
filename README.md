# Headline

``` mermaid
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John:hello John
    loop healthcheck
        John-->>John:fight against
    end
    Note right of John:rational
    
    John->>Alice:great!
    John->>Bob:how about you
    Bob->>John:good!

```