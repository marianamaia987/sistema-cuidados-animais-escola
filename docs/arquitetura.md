# Arquitetura do Sistema de Cuidado dos Animais da Escola

## Fluxograma

```mermaid
flowchart TD
    A[INICIO] --> B[Acessar o sistema]
    B --> C[Menu principal]
    C --> D[Escolher uma opcao]
    D --> E[Animais]
    D --> F[Cuidados]
    D --> G[Ocorrencias]
    E --> H[Consultar animais]
    F --> I[Registrar cuidado]
    G --> J[Registrar ocorrencia]
    H --> K[Salvar dados]
    I --> K
    J --> K
    K --> L[FIM]
