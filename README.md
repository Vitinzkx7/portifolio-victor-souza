#  Portfólio Victor Souza

<div align="center">

![Next.js](https://img.shields.io/badge/Next.js-14-black?style=for-the-badge&logo=next.js)
![React](https://img.shields.io/badge/React-18-61DAFB?style=for-the-badge&logo=react)
![TypeScript](https://img.shields.io/badge/TypeScript-5-3178C6?style=for-the-badge&logo=typescript)
![Python](https://img.shields.io/badge/Python-3.11-3776AB?style=for-the-badge&logo=python)
![Java](https://img.shields.io/badge/Java-17-ED8B00?style=for-the-badge&logo=openjdk)
![MySQL](https://img.shields.io/badge/MySQL-8.0-4479A1?style=for-the-badge&logo=mysql)




</div>

---

##  Sobre o Projeto

Olá, eu sou Victor Souza, sou Técnico em Automação Industrial e Estudante do 2º Período de Ciência da Computação na Unileste. Apaixonado por Tecnologia e Ciência de Dados, com objetivo de se tornar Cientista de Dados.
Foram 4 Árduos meses,mas finalmente consegui terminar meu portifólio.
Este projeto demonstra habilidades em desenvolvimento full-stack, integrando múltiplas tecnologias e frameworks modernos em uma aplicação completa e funcional.

###  Funcionalidades Principais

- 🎨 **Design Moderno**: Interface com tema escuro e azul neon vibrante
- 👤 **Perfil Dinâmico**: Seção hero com foto de perfil e informações pessoais
- 💼 **Portfólio de Projetos**: Integração com GitHub API para exibir repositórios
- 🛠️ **Habilidades Técnicas**: Categorização de skills por nível de proficiência
- 📜 **Certificações**: Exibição de certificados e conquistas acadêmicas
- 💬 **Sistema de Comentários**: Visitantes podem deixar feedback com avaliação por estrelas
- 📧 **Formulário de Contato**: Integrado com Web3Forms para envio de emails
- 🔐 **Autenticação JWT**: Sistema completo de login e registro
- 📱 **Responsivo**: Design adaptável para todos os dispositivos
- 🗄️ **Banco de Dados MySQL**: Persistência de dados com relacionamentos complexos

---

## 🛠️ Tecnologias Utilizadas

### Frontend

| Tecnologia | Versão | Descrição |
|------------|--------|-----------|
| **Next.js** | 14 | Framework React com App Router |
| **React** | 18 | Biblioteca para interfaces de usuário |
| **TypeScript** | 5 | Superset JavaScript com tipagem estática |
| **Tailwind CSS** | 4 | Framework CSS utility-first |
| **shadcn/ui** | Latest | Componentes UI reutilizáveis |
| **SWR** | Latest | React Hooks para data fetching |

### Backend

#### Python - FastAPI
- **FastAPI**: Framework web moderno e rápido
- **SQLAlchemy**: ORM para MySQL
- **Pydantic**: Validação de dados
- **Uvicorn**: Servidor ASGI
- **MySQL Connector**: Driver MySQL

#### Python - Flask
- **Flask**: Microframework web
- **Flask-SQLAlchemy**: Integração SQLAlchemy
- **Flask-CORS**: Suporte CORS
- **MySQL Connector**: Driver MySQL

#### Java - Spring Boot
- **Spring Boot**: Framework Java empresarial
- **Spring Security**: Autenticação e autorização
- **Spring Data JPA**: Persistência de dados
- **JWT (jjwt)**: Tokens de autenticação
- **MySQL Connector**: Driver JDBC MySQL
- **WebClient**: Cliente HTTP reativo

### Banco de Dados

- **MySQL 8.0**: Sistema de gerenciamento de banco de dados relacional
- **10 Tabelas**: users, skills, projects, contacts, experiences, education, certifications, testimonials, social_links, audit_logs
- **Relacionamentos**: Chaves estrangeiras e índices otimizados
- **Views**: Consultas pré-definidas para performance
- **Stored Procedures**: Operações complexas encapsuladas

---

## 📁 Estrutura do Projeto

\`\`\`
victor-portfolio/
│
├── 📂 app/                          # Next.js App Router
│   ├── layout.tsx                   # Layout principal com AuthProvider
│   ├── page.tsx                     # Página inicial
│   └── globals.css                  # Estilos globais e design tokens
│
├── 📂 components/                   # Componentes React
│   ├── hero.tsx                     # Seção hero com foto de perfil
│   ├── about.tsx                    # Sobre mim
│   ├── skills.tsx                   # Habilidades técnicas
│   ├── github-projects.tsx          # Projetos do GitHub
│   ├── certifications.tsx           # Certificações
│   ├── testimonials.tsx             # Comentários de visitantes
│   ├── contact.tsx                  # Formulário de contato
│   ├── navbar.tsx                   # Barra de navegação
│   ├── auth-modal.tsx               # Modal de login/registro
│   └── footer.tsx                   # Rodapé
│
├── 📂 lib/                          # Utilitários e contextos
│   ├── api-client.ts                # Cliente HTTP para APIs
│   ├── auth-context.tsx             # Contexto de autenticação JWT
│   └── utils.ts                     # Funções utilitárias
│
├── 📂 backend/                      # Backends
│   │
│   ├── 📂 fastapi/                  # API Python FastAPI
│   │   ├── main.py                  # Aplicação principal
│   │   ├── database.py              # Configuração SQLAlchemy
│   │   ├── models.py                # Modelos ORM
│   │   ├── schemas.py               # Schemas Pydantic
│   │   ├── requirements.txt         # Dependências Python
│   │   └── .env.example             # Exemplo de variáveis de ambiente
│   │
│   ├── 📂 flask/                    # API Python Flask
│   │   ├── app.py                   # Aplicação principal
│   │   ├── config.py                # Configurações
│   │   ├── models.py                # Modelos SQLAlchemy
│   │   ├── requirements.txt         # Dependências Python
│   │   └── .env.example             # Exemplo de variáveis de ambiente
│   │
│   └── 📂 spring-boot/              # API Java Spring Boot
│       ├── src/main/java/com/victorsouza/portfolio/
│       │   ├── PortfolioAuthApplication.java
│       │   ├── controller/          # Controllers REST
│       │   ├── service/             # Lógica de negócio
│       │   ├── repository/          # Repositórios JPA
│       │   ├── model/               # Entidades JPA
│       │   ├── dto/                 # Data Transfer Objects
│       │   ├── security/            # Configuração JWT e Security
│       │   └── config/              # Configurações
│       ├── src/main/resources/
│       │   ├── application.properties
│       │   ├── application-dev.properties
│       │   └── application-prod.properties
│       ├── pom.xml                  # Dependências Maven
│       └── .env.example             # Exemplo de variáveis de ambiente
│
├── 📂 database/                     # Scripts SQL
│   ├── scripts/
│   │   ├── 01_create_database.sql   # Criação do banco
│   │   ├── 02_create_tables.sql     # Criação de tabelas
│   │   ├── 03_seed_data.sql         # Dados iniciais
│   │   ├── 04_create_views.sql      # Views
│   │   └── 05_create_procedures.sql # Stored procedures
│   └── README.md                    # Documentação do banco
│
├── 📂 public/                       # Arquivos estáticos
│   └── images/
│       └── victor-profile.jpg       # Foto de perfil
│
├── 📄 package.json                  # Dependências Node.js
├── 📄 tsconfig.json                 # Configuração TypeScript
├── 📄 next.config.mjs               # Configuração Next.js
├── 📄 tailwind.config.ts            # Configuração Tailwind
├── 📄 start-dev.sh                  # Script inicialização Linux/Mac
├── 📄 start-dev.bat                 # Script inicialização Windows
├── 📄 GUIA_INICIALIZACAO.md         # Guia de inicialização
├── 📄 BACKEND_INTEGRATION.md        # Documentação integração backend
└── 📄 README.md                     # Este arquivo
\`\`\`

---



## 📡 API Endpoints

### FastAPI (Port 8000)

| Método | Endpoint | Descrição | Auth |
|--------|----------|-----------|------|
| GET | `/api/skills` | Lista todas as habilidades | ❌ |
| POST | `/api/skills` | Criar nova habilidade | ❌ |
| GET | `/api/profile` | Informações do perfil | ❌ |
| POST | `/api/contact` | Enviar mensagem de contato | ❌ |
| GET | `/api/education` | Lista educação | ❌ |
| GET | `/api/experiences` | Lista experiências | ❌ |
| GET | `/docs` | Documentação Swagger | ❌ |

### Flask (Port 5000)

| Método | Endpoint | Descrição | Auth |
|--------|----------|-----------|------|
| GET | `/api/projects` | Lista todos os projetos | ❌ |
| GET | `/api/projects/<id>` | Detalhes de um projeto | ❌ |
| POST | `/api/projects` | Criar novo projeto | ❌ |
| GET | `/api/contacts` | Lista mensagens de contato | ❌ |
| GET | `/api/stats` | Estatísticas do portfólio | ❌ |

### Spring Boot (Port 8080)

| Método | Endpoint | Descrição | Auth |
|--------|----------|-----------|------|
| POST | `/api/auth/register` | Registrar novo usuário | ❌ |
| POST | `/api/auth/login` | Login de usuário | ❌ |
| POST | `/api/contact/send` | Enviar email via Web3Forms | ❌ |
| POST | `/api/contact/verify-email` | Verificar email | ✅ |
| GET | `/api/user/profile` | Perfil do usuário | ✅ |



##  Banco de Dados

### Estrutura de Tabelas

\`\`\`sql
portfolio_db
├── users                 # Usuários do sistema
├── skills                # Habilidades técnicas
├── projects              # Projetos do portfólio
├── contacts              # Mensagens de contato
├── experiences           # Experiências profissionais
├── education             # Formação acadêmica
├── certifications        # Certificações
├── testimonials          # Comentários de visitantes
├── social_links          # Links de redes sociais
└── audit_logs            # Logs de auditoria
\`\`\`

### Relacionamentos

- `skills` → `users` (many-to-one)
- `projects` → `users` (many-to-one)
- `experiences` → `users` (many-to-one)
- `education` → `users` (many-to-one)
- `certifications` → `users` (many-to-one)
- `testimonials` → `users` (many-to-one)

### Views Disponíveis

- `vw_user_profile`: Perfil completo do usuário
- `vw_active_projects`: Projetos ativos
- `vw_recent_contacts`: Contatos recentes

### Stored Procedures

- `sp_get_user_stats(user_id)`: Estatísticas do usuário
- `sp_add_skill(user_id, name, category, level)`: Adicionar habilidade
- `sp_log_contact(name, email, message)`: Registrar contato

---

## 🎨 Design System

### Paleta de Cores

\`\`\`css
/* Tema Escuro com Azul Neon */
--background: 0 0% 5%;           /* Preto profundo */
--foreground: 210 100% 95%;      /* Branco suave */
--primary: 210 100% 50%;         /* Azul neon vibrante */
--primary-glow: 210 100% 60%;    /* Brilho azul neon */
--accent: 180 100% 50%;          /* Ciano neon */
--muted: 217 33% 17%;            /* Cinza azulado */
\`\`\`

### Tipografia

- **Fonte Principal**: Geist Sans
- **Fonte Mono**: Geist Mono
- **Tamanhos**: 14px (base), 16px (corpo), 24-48px (títulos)

### Componentes UI

Utilizando **shadcn/ui** com customizações:
- Button, Card, Input, Textarea
- Dialog, Dropdown Menu, Avatar
- Badge, Alert, Spinner
- Accordion, Tabs, Toast

---
## 📚 Documentação Adicional

- [Guia de Inicialização](GUIA_INICIALIZACAO.md)
- [Integração Backend](BACKEND_INTEGRATION.md)
- [Configuração MySQL](database/README.md)
- [Setup Spring Boot](backend/spring-boot/MYSQL_SETUP.md)

---



## 📝 Licença

Este projeto é de uso pessoal para o portfólio de Victor Souza.

---

## 👤 Autor

**Victor Souza**

- Técnico em Automação Industrial
- Estudante de Ciência da Computação (2º Período) - Unileste
- Aspirante a Cientista de Dados

### Habilidades Técnicas

**Linguagens de Programação:**
- Python (Avançado)
- Java (Intermediário)
- JavaScript (Intermediário)
- C (Avançado)
- R (Iniciante)

**Desenvolvimento Web:**
- HTML (Avançado)
- CSS (Avnçado)
- Node.js (Intermediário)
- React (Intermediário)
- Next.js (Intermediário)

**Banco de Dados:**
- MySQL (Avançado)

**Frameworks:**
- FastAPI
- Flask
- Spring Boot
- Express.js

### Contato

- 📧 Email: victornex2006@hotmail.com
- 💼 LinkedIn: [linkedin.com/in/victor-souza-2b8096282](www.linkedin.com/in/victor-souza-2b8096282)
- 🐙 GitHub: [github.com/Vitinzkx7](https://github.com/Vitinzkx7)
- 🌐 Portfólio: [https://portifolio-zu5gnehma-victor-souzas-projects.vercel.app/)

---

## 🙏 Agradecimentos

- [Next.js](https://nextjs.org/) - Framework React
- [Tailwind CSS](https://tailwindcss.com/) - Framework CSS
- [shadcn/ui](https://ui.shadcn.com/) - Componentes UI
- [FastAPI](https://fastapi.tiangolo.com/) - Framework Python
- [Spring Boot](https://spring.io/projects/spring-boot) - Framework Java
- [Web3Forms](https://web3forms.com/) - Serviço de email
- [Vercel](https://vercel.com/) - Plataforma de deploy

---

<div align="center">

**⭐ Se este projeto foi útil, considere dar uma estrela!**

Desenvolvido  por Victor Souza

</div>
