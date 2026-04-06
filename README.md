# atividade-crystal
Cronograma e Matriz Crystal


Gráfico de Gantt (Cronograma)
```mermaid

   gantt
    title Cronograma TechConnect
    dateFormat  YYYY-MM-DD
    axisFormat  %b

    section Planejamento
    Requisitos e Documentação :a1, 2024-01-01, 25d

    section Design
    Criar o Visual do Sistema :b1, after a1, 25d

    section Programação
    Setup e Banco de Dados :c1, after b1, 10d
    Fazer Login e CRUD :c2, after c1, 40d
    Upload, Relatórios e Painel :c3, after c2, 50d

    section Testes e Entrega
    Testar tudo com QA e Usuários :d1, after c3, 25d
    Entregar o Sistema :e1, after d1, 5d

```

Matriz de Atenção Crystal Clear
```mermaid

   flowchart TD
    A[Foco do Projeto] --> B(O que vamos entregar)
    A --> C(Como vamos conversar)

    B --> D[Login e Cadastros]
    D -. Cuidado .-> D1[Segurança e Banco de Dados ok?]

    B --> E[Upload de Logos]
    E -. Cuidado .-> E1[Bloquear vírus e arquivos inválidos]

    B --> F[Relatórios e Painel]
    F -. Cuidado .-> F1[Garantir que ninguém veja o que não deve]

    C --> G[Reuniões Diárias]
    G -. Cuidado .-> G1[Ser rápido e não enrolar, focando no que importa]

    C --> H[Mostrar pra Diretoria]
    H -. Cuidado .-> H1[Ver se eles estão gostando e não fugir do escopo]
    
    style D1 fill:#f9d0c4,stroke:#333,stroke-width:2px
    style E1 fill:#f9d0c4,stroke:#333,stroke-width:2px
    style F1 fill:#f9d0c4,stroke:#333,stroke-width:2px
    style G1 fill:#fef0bd,stroke:#333,stroke-width:2px
    style H1 fill:#fef0bd,stroke:#333,stroke-width:2px

```
