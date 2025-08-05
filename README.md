# Sempre que uma edição for feita, esta seção será atualizada com as melhorias ou implementações realizadas.


# NoxMedia Studio

Painel administrativo e frontend moderno para gerenciamento de tickets e suporte.

## Como rodar o projeto

1. Instale as dependências: npm install
2. Rode o projeto em modo desenvolvimento: npm run dev
3. Acesse em [http://localhost:5173](http://localhost:5173)

## Tecnologias
- React + TypeScript
- TailwindCSS
- Lucide Icons
- Vite

## Changelog

### [Data da alteração mais recente]
- Removido completamente o Picmo (emoji picker) do projeto, incluindo todas as dependências, imports e código relacionado a emojis.

### [04/08/2023]
- Grid de estatísticas agora é fixo (sticky) no topo do painel, sem scroll
- Layout do AdminPanel ocupa 100% do viewport
- Melhor responsividade em telas pequenas
- Ajuste dos paddings e gaps para diferentes breakpoints
- Sidebar e chat area com scroll independente
- Adição de variações de tamanho para mobile/desktop
- Otimização do layout para telas menores
- Troca do gradiente verde para azul nos cards de estatísticas para um visual mais moderno
- **Redesign visual e estrutural do chat do usuário (UserChat):**
  - Header com avatar, nome do bot/empresa e status online
  - Container arredondado, sombra suave, rolagem interna
  - Balões de mensagem modernos, quick replies estilizados, botão “Falar com Humano” sempre visível
  - Input fixo com emoji e envio, timestamp discreto, links estilizados
  - Responsividade total, pronto para futuras features (reação, busca, editar/excluir, etc.)

## Funcionalidades do Chat (WhatsApp-like)

- Autoscroll automático para o final da conversa ao receber novas mensagens, **apenas se o usuário estiver no final**.
- Se o usuário rolar para cima (lendo mensagens antigas), o autoscroll é pausado para não interromper a leitura.
- Ao voltar para o final, o autoscroll volta a funcionar normalmente.
- O scroll é suave e automático, sem necessidade de interação manual.
- Ao abrir uma nova conversa ou reiniciar o chat, o scroll sempre começa no final.
- **Seta para descer:** Quando o usuário está longe do final da conversa, aparece uma seta/flutuante (ícone) para descer rapidamente para o final do chat.

## UX
- Comportamento de rolagem igual ao WhatsApp.
- Seta de rolagem implementada com ícone React (ChevronDown/Lucide).
- Experiência fluida tanto para mensagens enviadas quanto recebidas.

### [Versão Inicial]
- Criação do README inicial
- Implementação inicial do AdminPanelPage

---
Sempre que uma edição for feita, esta seção será atualizada com as melhorias ou implementações realizadas.
