# SITE_Inicio_Com_BD
Treinamento estruturado 

```
SITE-CADASTRO/
│
├── frontend/         # Vite com TypeScript
│   ├── index.html
│   ├── vite.config.ts
│   ├── tsconfig.json
│   └── src/
│       ├── main.ts
│       ├── App.tsx
│       ├── pages/
│       │   ├── Login.tsx
│       │   └── Register.tsx
│       └── services/
│           └── api.ts       # Conexão com backend
│
├── backend/          # PHP
│   ├── config/
│   │   └── db.php           # Conexão com banco
│   ├── controllers/
│   │   ├── login.php
│   │   └── register.php
│   ├── utils/
│   │   └── functions.php    # Funções úteis (ex: validação)
│   └── .htaccess            # Proteção de diretórios (Apache)
│
└── database/
    └── schema.sql           # Script SQL para criar as tabelas

```
