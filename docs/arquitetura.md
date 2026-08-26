flowchart TD
    A([INÍCIO]) --> B[Acessar o sistema]
    B --> C[Menu principal]
    C --> D{Escolher opção}

    D --> E[Animais]
    D --> F[Cuidados]
    D --> G[Ocorrências]

    E --> H[Consultar animais]
    F --> I[Registrar cuidado]
    G --> J[Registrar ocorrência]

    H --> K[Salvar dados]
    I --> K
    J --> K

    K --> L([FIM])
