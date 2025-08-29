# Hair Day

Uma **aplicação web de agendamento para corte de cabelo** moderna e responsiva, criada durante o curso da **Rocketseat**.  
Permite agendar horários de atendimento, visualizar disponibilidade em tempo real e gerenciar agendamentos organizados por períodos do dia (manhã, tarde e noite).

---

## Visão Geral

- **HTML5**: marcação semântica com `<form>`, `<aside>`, `<section>`, `<header>` e elementos de lista organizados.  
- **CSS3**: variáveis (Custom Properties), Flexbox & CSS Grid, transições suaves, design responsivo e interface moderna.  
- **JavaScript ES6+**: módulos organizados, manipulação dinâmica do DOM, validação de formulários e integração com API REST.  
- **Webpack**: bundling de módulos, desenvolvimento com hot reload e build otimizado para produção.  
- **JSON Server**: API REST simulada para persistência de dados dos agendamentos.

---

## Estrutura do Projeto

- **`index.html`**: página principal com formulário de agendamento e visualização de horários.  
- **`global.css`**: estilos globais com variáveis, reset, layout e responsividade.  
- **`form.css`**: estilos específicos do formulário com validações visuais e estados interativos.  
- **`schedule.css`**: estilos da área de visualização de agendamentos por período.  
- **`src/modules/`**: módulos JavaScript organizados por funcionalidade específica.  
- **`src/assets/`**: ícones SVG e recursos visuais da interface.

---

## Principais Funcionalidades

- **Seleção de Data** – calendário interativo com validação de datas futuras.  
- **Horários Dinâmicos** – exibição automática de horários disponíveis e ocupados.  
- **Agendamento Rápido** – formulário intuitivo com validação em tempo real.  
- **Visualização por Períodos** – organização clara em manhã, tarde e noite.  
- **Cancelamento de Agendamentos** – remoção rápida com confirmação visual.  
- **Interface Responsiva** – adaptação perfeita para desktop, tablet e mobile.  
- **Feedback Visual** – estados visuais claros para horários disponíveis/ocupados.

---

## Como Executar

```bash
# Instalar dependências
npm install

# Iniciar servidor de desenvolvimento
npm run dev

# Iniciar API (em outro terminal)
npm run server

# Build para produção
npm run build
```

---

## Tecnologias Utilizadas

- **Frontend**: HTML5, CSS3, JavaScript ES6+
- **Build Tool**: Webpack 5
- **Bundling**: Babel, CSS Loader, Style Loader, Copy Webpack Plugin
- **API**: JSON Server com Nodemon
- **Formatação de Datas**: Day.js
- **Design**: Mobile First, CSS Grid, Flexbox, Custom Properties

---

## Estrutura de Horários

- **Manhã**: 08h às 12h (8:00 - 12:00)
- **Tarde**: 13h às 17h (13:00 - 17:00)  
- **Noite**: 18h às 21h (18:00 - 21:00)

---

<img width="1870" height="992" alt="Captura de tela de 2025-08-29 12-33-03" src="https://github.com/user-attachments/assets/84f1a097-fc0e-414b-b1a0-3af390ad3afe" />

---

<p align="center">
  Desenvolvido durante o curso da <strong>Rocketseat</strong> com <img src="src/assets/heart.svg" width="14" alt="coração"/> por <strong>@mayasrl</strong>.
</p>
