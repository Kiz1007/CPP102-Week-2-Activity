flowchart TD
    A([Start]) --> B[/Input Number/]
    B --> C[Store Number]
    C --> D{Number MOD 2 = 0?}
    D -- Yes --> E[/Display "Even"/]
    D -- No --> F[/Display "Odd"/]
    E --> G([End])
    F --> G([End])
