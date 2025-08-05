# 🎬 NoxMedia Studio

<div align="center">
  
**A plataforma completa para democratizar a acessibilidade de vídeos**

[![Open Source](https://img.shields.io/badge/Open%20Source-💚-success)](https://github.com/PhilippeBoechat/NoxMedia)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![React](https://img.shields.io/badge/React-18+-61DAFB?logo=react)](https://reactjs.org/)
[![TypeScript](https://img.shields.io/badge/TypeScript-5+-3178C6?logo=typescript)](https://www.typescriptlang.org/)
[![Vite](https://img.shields.io/badge/Vite-5+-646CFF?logo=vite)](https://vitejs.dev/)

[🚀 Demo Live](https://noxmedia.studio) • [📚 Documentação](https://docs.noxmedia.studio) • [💬 Discord](https://discord.com/invite/VG5hmeGbbj) • [🐛 Report Bug](https://github.com/PhilippeBoechat/NoxMedia/issues)

</div>

---

## ✨ Sobre o Projeto

**NoxMedia Studio** é uma plataforma moderna e intuitiva que combina **gerenciamento inteligente de tickets de suporte** com **edição automática de legendas de vídeo** alimentada por IA. Nossa missão é tornar a criação de conteúdo acessível **gratuita, rápida e profissional** para criadores, empresas e organizações.

### 🎯 Por que NoxMedia?

- **🤖 IA Integrada**: Legendas automáticas com precisão profissional
- **⚡ Performance**: Interface ultrarrápida construída com Vite + React
- **🎨 UX Moderna**: Design responsivo e experiência mobile-first
- **🔓 100% Gratuito**: Open source com licença permissiva
- **🌍 Acessibilidade**: Democratizando o acesso a conteúdo audiovisual

---

## 🚀 Funcionalidades Principais

### 🎬 **Editor de Legendas Avançado**
- **Upload inteligente** de vídeos (MP4, AVI, MOV, WebM)
- **Geração automática** de legendas com IA de última geração
- **Editor visual** com timeline sincronizada
- **Exportação múltipla** (SRT, VTT, TXT, JSON)
- **Preview em tempo real** com player integrado

### 🎧 **Sistema de Suporte Inteligente**
- **Chatbot com IA** para atendimento 24/7
- **Tickets organizados** por prioridade e categoria
- **Dashboard administrativo** com métricas em tempo real
- **Notificações push** e atualizações automáticas
- **Histórico completo** de interações

### 📊 **Painel Administrativo**
- **Análises detalhadas** de uso e performance
- **Gerenciamento de usuários** e permissões
- **Estatísticas em tempo real** com gráficos interativos
- **Controle de qualidade** de atendimento
- **Relatórios exportáveis** (PDF, Excel)

---

## 🛠️ Stack Tecnológica

<div align="center">

| Frontend | Styling | Build | Icons | State |
|----------|---------|-------|-------|-------|
| ![React](https://img.shields.io/badge/React-18.2+-61DAFB?style=for-the-badge&logo=react) | ![TailwindCSS](https://img.shields.io/badge/Tailwind-3.4+-06B6D4?style=for-the-badge&logo=tailwindcss) | ![Vite](https://img.shields.io/badge/Vite-5.0+-646CFF?style=for-the-badge&logo=vite) | ![Lucide](https://img.shields.io/badge/Lucide-Icons-F56565?style=for-the-badge) | ![Context API](https://img.shields.io/badge/Context-API-61DAFB?style=for-the-badge) |

</div>

### Principais Dependências
```json
{
  "react": "^18.2.0",
  "typescript": "^5.2.2",
  "vite": "^5.0.0",
  "tailwindcss": "^3.4.0",
  "lucide-react": "^0.263.1"
}
```

---

## ⚡ Instalação Rápida

### Pré-requisitos
- **Node.js** 18+ ([Download](https://nodejs.org/))
- **npm** ou **yarn**
- **Git** ([Download](https://git-scm.com/))

### Passos de Instalação

1. **Clone o repositório**
   ```bash
   git clone https://github.com/PhilippeBoechat/NoxMedia.git
   cd NoxMedia
   ```

2. **Instale as dependências**
   ```bash
   npm install
   # ou
   yarn install
   ```

3. **Execute em modo desenvolvimento**
   ```bash
   npm run dev
   # ou
   yarn dev
   ```

4. **Acesse a aplicação**
   ```
   🌐 http://localhost:5173
   ```

### Scripts Disponíveis
```bash
npm run dev      # Servidor de desenvolvimento
npm run build    # Build para produção
npm run preview  # Preview do build
npm run type-check # Verificação de tipos TypeScript
```

---

## 🌐 Deploy em Produção

### Deploy Automático

| Plataforma | Status | Configuração |
|------------|--------|--------------|
| [![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel)](https://vercel.com) | ✅ Recomendado | Auto-deploy via Git |
| [![Netlify](https://img.shields.io/badge/Netlify-00C7B7?style=for-the-badge&logo=netlify)](https://netlify.com) | ✅ Suportado | Drag & drop ou Git |
| [![Render](https://img.shields.io/badge/Render-46E3B7?style=for-the-badge&logo=render)](https://render.com) | ✅ Suportado | Static site |

### Configuração Manual
1. **Build do projeto**: `npm run build`
2. **Servir pasta `dist`** com servidor estático
3. **Configurar variáveis de ambiente** (se necessário)

---

## 🤝 Como Contribuir

Adoramos contribuições da comunidade! Aqui está como você pode ajudar:

### 🐛 Reportar Bugs
1. Verifique se o bug já foi reportado em [Issues](https://github.com/PhilippeBoechat/NoxMedia/issues)
2. Crie uma nova issue com template detalhado
3. Inclua screenshots e passos para reproduzir

### ✨ Sugerir Features
1. Abra uma **Feature Request** no GitHub
2. Descreva detalhadamente sua ideia
3. Explique como beneficiaria os usuários

### 💻 Contribuir com Código
1. **Fork** o repositório
2. **Clone** seu fork localmente
   ```bash
   git clone https://github.com/seu-usuario/NoxMedia.git
   ```
3. **Crie uma branch** para sua feature
   ```bash
   git checkout -b feature/minha-nova-feature
   ```
4. **Commit** suas mudanças
   ```bash
   git commit -m "feat: adiciona nova funcionalidade X"
   ```
5. **Push** para seu fork
   ```bash
   git push origin feature/minha-nova-feature
   ```
6. **Abra um Pull Request** no repositório original

### 📋 Padrões de Commit
Utilizamos [Conventional Commits](https://www.conventionalcommits.org/):
```
feat: nova funcionalidade
fix: correção de bug
docs: atualização de documentação
style: formatação/estilo
refactor: refatoração de código
test: adição de testes
chore: tarefas de manutenção
```

---

## 📈 Roadmap

### 🎯 Próximas Features (Q1 2025)
- [ ] **API REST completa** para integração externa
- [ ] **Plugin para WordPress** e editores populares
- [ ] **Suporte a mais idiomas** (50+ línguas)
- [ ] **Templates de legendas** pré-configurados
- [ ] **Colaboração em tempo real** para equipes

### 🚀 Visão de Longo Prazo
- [ ] **Mobile App** (React Native)
- [ ] **Integração com YouTube/Vimeo** automática
- [ ] **IA ainda mais avançada** para contexto e emoções
- [ ] **Marketplace de templates** da comunidade
- [ ] **Análise de sentimentos** em legendas

---

## 📊 Estatísticas do Projeto

<div align="center">

![GitHub stars](https://img.shields.io/github/stars/PhilippeBoechat/NoxMedia?style=social)
![GitHub forks](https://img.shields.io/github/forks/PhilippeBoechat/NoxMedia?style=social)
![GitHub issues](https://img.shields.io/github/issues/PhilippeBoechat/NoxMedia)
![GitHub contributors](https://img.shields.io/github/contributors/PhilippeBoechat/NoxMedia)
![GitHub last commit](https://img.shields.io/github/last-commit/PhilippeBoechat/NoxMedia)

</div>

---

## 📄 Licença

Este projeto está licenciado sob a **MIT License** - veja o arquivo [LICENSE](LICENSE) para detalhes.

**Isso significa que você pode:**
- ✅ Usar comercialmente
- ✅ Modificar o código
- ✅ Distribuir
- ✅ Usar em projetos privados

---

## 📞 Suporte e Contato

### 🆘 Precisa de Ajuda?

| Canal | Resposta | Descrição |
|-------|----------|-----------|
| 💬 [Discord](https://discord.com/invite/VG5hmeGbbj) | Tempo real | Chat da comunidade |
| 📧 [Email](mailto:suporte@noxmedia.studio) | 24-48h | Suporte técnico |
| 🐛 [GitHub Issues](https://github.com/PhilippeBoechat/NoxMedia/issues) | 2-7 dias | Bugs e features |
| 📚 [Documentação](https://docs.noxmedia.studio) | Instantâneo | Guias e tutoriais |

### 🌟 Conecte-se Conosco

<div align="center">

[![Discord](https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)](https://discord.com/invite/VG5hmeGbbj)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/PhilippeBoechat/NoxMedia)
[![Email](https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:suporte@noxmedia.studio)

</div>

---

<div align="center">

**🎬 NoxMedia Studio** — Democratizando a acessibilidade de vídeos com tecnologia aberta

*Feito com* 💙 *pela comunidade, para a comunidade*

⭐ **Gostou do projeto? Deixe uma estrela no GitHub!** ⭐

</div>
