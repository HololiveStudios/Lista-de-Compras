# Lista de Compras - Smart Shopping List

## 1. Objetivo e Finalidade
Aplicativo inteligente para gerenciamento de listas de compras, controle de despesas e categorização de itens de supermercado.

## 2. Tecnologias Utilizadas
- React, TypeScript, Vite, Tailwind CSS, TanStack Query, Chart.js, Firebase, Framer Motion, Lucide React

## 3. Arquitetura e Estrutura de Diretórios
Single Page Application (SPA) com React e Vite. Gestão de estado de servidor com TanStack React Query e persistência em nuvem via Firebase. Visualizações analíticas com Chart.js.

## 4. Principais Arquivos e Responsabilidades
- `src/App.tsx`: Aplicação principal e gerenciamento da lista de produtos.
- `firebase.json`: Integração e deploy no Firebase Hosting.
- `package.json`: Gerenciamento de bibliotecas analíticas e de interface.

## 5. Funcionalidades Identificadas
- Adição, edição e marcação de itens da lista de compras
- Gráficos analíticos de despesas por categoria via Chart.js
- Cache e sincronização de dados via TanStack Query
- Interface fluida com animações via Framer Motion

## 6. Como Compilar ou Executar
```bash
npm install
npm run dev
# Build de produção: npm run build
```

## 7. Estado Atual do Projeto
**Completo**

## 8. Pendências e Limitações Identificadas
Adicionar leitura de código de barras ou reconhecimento óptico de cupons fiscais.
