 📚 EstudaAí - Plataforma de Estudos

Plataforma interativa de estudos para o Ensino Médio, com conteúdo organizado por matéria, sistema de progresso e gamificação.

## ✨ Funcionalidades

- **12 matérias** do Ensino Médio com conteúdo resumido
- **Sistema de XP e níveis** para motivar o estudo
- **Progresso por matéria** com barra visual
- **Streak de estudos** (dias consecutivos)
- **Conteúdo estruturado** com resumos, pontos-chave e exemplos

## 🛠️ Tecnologias Utilizadas

- **React** — Biblioteca para construção da interface
- **TypeScript** — Tipagem estática para JavaScript
- **Vite** — Ferramenta de build rápida
- **Tailwind CSS** — Framework de estilização
- **shadcn/ui** — Componentes de interface reutilizáveis
- **Lucide React** — Ícones

## 🚀 Como rodar o projeto localmente

Pré-requisito: ter o [Node.js](https://nodejs.org/) instalado (versão 18 ou superior).

```bash
# 1. Clone o repositório
git clone <URL_DO_REPOSITORIO>

# 2. Entre na pasta do projeto
cd estudaai

# 3. Instale as dependências
npm install

# 4. Inicie o servidor de desenvolvimento
npm run dev
```

O site abrirá automaticamente em `http://localhost:5173`.

## 📁 Estrutura do Projeto

```
src/
├── components/       # Componentes visuais (Header, Cards, etc.)
├── data/             # Dados das matérias e conteúdos dos tópicos
├── hooks/            # Hooks customizados (progresso, XP)
├── pages/            # Páginas da aplicação
└── lib/              # Funções utilitárias
```

## 📝 Como funciona

1. Na tela inicial, escolha uma **matéria** (Matemática, Física, etc.)
2. Veja os **tópicos** disponíveis e clique em um para estudar
3. Leia o **resumo**, os **pontos-chave** e o **exemplo**
4. Marque o tópico como **concluído** para ganhar **+25 XP**
5. Acompanhe seu **nível** e **streak** na barra superior

## 👨‍💻 Desenvolvido com

Projeto criado utilizando a plataforma [Lovable](https://lovable.dev).
