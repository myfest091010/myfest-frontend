myfest_cloud_manager/
├── backend/               # Servidor API Express
│   ├── prisma/            # Esquema e migrações do banco de dados
│   ├── src/               # Código-fonte do backend
│   │   ├── controllers/   # Controladores de API
│   │   ├── routes/        # Rotas da API
│   │   ├── services/      # Serviços de integração
│   │   ├── middleware/    # Middlewares
│   │   ├── utils/         # Utilitários
│   │   └── config/        # Configurações
│   └── package.json       # Dependências do backend
├── frontend/              # Aplicação Next.js
│   ├── components/        # Componentes React reutilizáveis
│   ├── contexts/          # Contextos React (autenticação, etc.)
│   ├── pages/             # Páginas da aplicação
│   ├── styles/            # Estilos CSS
│   ├── public/            # Arquivos estáticos
│   └── package.json       # Dependências do frontend
├── docs/                  # Documentação
│   ├── documentacao.md    # Documentação completa do sistema
│   ├── guia_implantacao.md # Guia de implantação em produção
│   └── plano_de_testes.md # Plano de testes detalhado
└── start.sh              # Script de inicialização
