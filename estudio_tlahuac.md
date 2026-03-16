graph TD
    %% Título Principal
    Inicio((Abordaje Sistémico:<br/>Cambio Climático en Tláhuac))
    
    %% Nivel 1: Estructura del Ensayo
    Inicio --> P1[1. Problemática:<br/>Análisis desde la Carta de la Tierra]
    Inicio --> P2[2. Marco Epistémico:<br/>Saber Ambiental e Ideología]
    Inicio --> P3[3. Metodología:<br/>Sistemas Complejos e Interdisciplina]

    %% Nivel 2: Desglose Problemática (Carta de la Tierra)
    P1 --> E1[Ecología Integral:<br/>Ruptura de la totalidad de relaciones]
    P1 --> E2[Ecología Ambiental:<br/>Potenciador de presiones hídricas]
    P1 --> E3[Ecología Social:<br/>Vulnerabilidad de marginados y saberes]
    P1 --> E4[Ecología Mental:<br/>Cosmovisiones vs. Mentalidad moderna]

    %% Nivel 2: Desglose Epistémico
    P2 --> LE[Enrique Leff:<br/>Saber Ambiental]
    LE --> RA[Racionalidad Ambiental:<br/>Justicia y Reproducción de la Vida]
    RA --> Critica[Crítica al modelo extractivista e inmobiliario]

    %% Nivel 2: Desglose Metodológico
    P3 --> RG[Rolando García:<br/>Sistemas Complejos]
    RG --> Inter[Interdisciplina:<br/>Interdefinibilidad de componentes]
    
    %% Componentes del Sistema Tláhuac
    Inter --> Sistema{Sistema Socio-Ecológico}
    Sistema --> Bio[Biofísicos:<br/>Suelo, Agua, Biodiversidad]
    Sistema --> Soc[Sociales:<br/>Chinampas, Cultura, Política]

    %% Conexiones Cruzadas (Sistémicas)
    E1 -.-> Sistema
    Critica -.-> Soc
    
    %% Estilos
    style Inicio fill:#f9f,stroke:#333,stroke-width:4px
    style P1 fill:#bbf,stroke:#333
    style P2 fill:#bbf,stroke:#333
    style P3 fill:#bbf,stroke:#333
    style Sistema fill:#dfd,stroke:#333,stroke-dasharray: 5 5
