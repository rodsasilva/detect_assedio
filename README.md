# Detecção de assédio
O objetivo do aplicativo é detectar e oferecer suporte para quem está sofrendo assédio moral.
```mermaid
graph TD
    A[Usuário Acessa App] --> B[Login/Registro]
    B --> C[Dashboard Principal]
    
    C --> D[Relatar Situação]
    C --> E[Chat com IA]
    C --> F[Recursos Educativos]
    C --> G[Suporte]

    D --> H[Formulário Estruturado]
    H --> I[Análise por IA]
    
    I --> J{Classificação}
    J -->|Alto Risco| K[Alerta Imediato]
    J -->|Médio Risco| L[Recomendações]
    J -->|Baixo Risco| M[Orientações]
    
    E --> N[Chat Anônimo]
    N --> O[Análise do Caso]
    
    F --> P[Material Informativo]
    F --> Q[Legislação]
    
    G --> R[Contatos de Ajuda]
    G --> S[Órgãos Competentes]
```

# Estrutura do Projeto

```
Detecção de assédio/
├── frontend/               # React Frontend
│   ├── src/
│   │   ├── components/     # Componentes React
│   │   ├── pages/          # Páginas da aplicação
│   │   ├── services/       # Serviços de API
│   │   ├── contexts/       # Contextos React
│   │   └── hooks/          # Custom hooks
│   └── package.json
│
├── backend/                # Python Backend
│   ├── app/
│   │   ├── routes/         # Rotas da API
│   │   ├── models/         # Modelos do banco
│   │   ├── services/       # Lógica de negócio
│   │   └── ai/             # Integrações com IA
│   ├── requirements.txt
│   └── main.py
│
└── docker-compose.yml       # Configuração dos containers
```

