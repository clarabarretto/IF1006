# 🏗️ Guia de Construção do Veredicto

> **Nota Importante**: Este documento representa uma proposta inicial de estrutura do projeto. A organização e estruturação estão em análise e podem ser modificadas conforme o desenvolvimento.

## 📁 Estrutura Proposta do Projeto

```
veredicto/
├── backend/
│   ├── src/
│   │   ├── api/                 # Endpoints da API
│   │   ├── core/               # Lógica de negócio principal
│   │   │   ├── embeddings/     # Geração e gerenciamento de embeddings
│   │   │   ├── rag/           # Implementação do pipeline RAG
│   │   │   └── scoring/       # Sistema de pontuação de viabilidade
│   │   ├── data/              # Processamento e gerenciamento de dados
│   │   │   ├── collectors/    # Coletores de dados jurisprudenciais
│   │   │   └── processors/    # Utilitários de processamento de texto
│   │   └── utils/             # Funções auxiliares
│   ├── tests/                 # Testes do backend
│   └── requirements.txt       # Dependências
│
├── frontend/
│   ├── src/
│   │   ├── components/        # Componentes da interface
│   │   ├── pages/            # Páginas da aplicação
│   │   ├── services/         # Integração com API
│   │   └── utils/            # Utilitários do frontend
│   ├── public/               # Arquivos estáticos
│   └── package.json          # Dependências
│
├── data/
│   ├── raw/                  # Dados jurisprudenciais brutos
│   ├── processed/            # Dados processados e limpos
│   └── embeddings/           # Embeddings gerados
│
├── docs/                     # Documentação
│   ├── api/                 # Documentação da API
│   └── architecture/        # Decisões de arquitetura
│
└── scripts/                  # Scripts utilitários
    ├── data_collection/     # Scripts de coleta de dados
    └── setup/               # Scripts de configuração
```

## 🔄 Fluxo de Desenvolvimento

1. **Fase de Análise (Em Andamento)**
   - Definição da estrutura do projeto
   - Análise de requisitos
   - Planejamento inicial

2. **Fase de Setup**
   - Configuração do ambiente
   - Estruturação do repositório
   - Definição de padrões

3. **Fase de Implementação**
   - Desenvolvimento iterativo
   - Testes
   - Documentação

## 📋 Próximos Passos

1. **Estruturação**
   - [ ] Definir estrutura final do projeto
   - [ ] Configurar ambiente de desenvolvimento
   - [ ] Estruturar repositório

2. **Desenvolvimento Inicial**
   - [ ] Implementar coleta de dados
   - [ ] Desenvolver pipeline básico
   - [ ] Criar interface inicial

## ⚠️ Considerações Importantes

1. **Organização**
   - Manter estrutura clara e organizada
   - Facilitar manutenção
   - Permitir expansão

2. **Documentação**
   - Documentar decisões
   - Manter documentação atualizada
   - Facilitar onboarding

---

> **Status**: Este documento está em desenvolvimento e será atualizado conforme o projeto evolui.
