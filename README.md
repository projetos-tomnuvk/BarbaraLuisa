# Barbara Luisa — Portfolio de Social Media

Site pessoal desenvolvido para uma Social Media & Criadora de Conteúdo, com foco em design editorial, performance e funcionalidades reais de gerenciamento de conteúdo.

## Tecnologias utilizadas

- **HTML5** — estrutura semântica e acessível
- **CSS3** — layout com Grid e Flexbox, animações, efeitos com `clip-path`, `mix-blend-mode` e `drop-shadow`
- **JavaScript (Vanilla)** — sem frameworks, lógica de upload, autenticação e renderização dinâmica
- **Supabase** — backend as a service para autenticação (Auth) e armazenamento de vídeos (Storage)
- **GitHub Pages** — hospedagem estática gratuita

## Funcionalidades

- Design responsivo com tipografia editorial (Playfair Display + Syne)
- Cursor customizado animado
- Animações de scroll com Intersection Observer
- Seção de portfólio com vídeos carregados dinamicamente via Supabase Storage
- Sistema de upload de vídeos com barra de progresso e legenda opcional
- Autenticação real via Supabase Auth — área admin protegida por login
- Botão flutuante de WhatsApp
- Proteção de rotas sensíveis via RLS (Row Level Security) no Supabase

## Deploy

Hospedado via **GitHub Pages** com armazenamento de mídia no **Supabase**.
