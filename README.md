# NebulaX

> **O frontend definitivo e elegante para seus jogos clássicos de PS1, PS2 e PSP.**

🚀 **LANÇAMENTO OFICIAL DA V1.0.0: 17 de Setembro** 🚀

O repositório está sendo preparado para o lançamento público da primeira versão executável. Marque este repositório com uma ⭐ (Star) para ser notificado assim que o download estiver disponível na aba de Releases!

---

## 🎮 Sobre o Projeto

O **NebulaX** nasceu da vontade de transformar o PC em um verdadeiro console de mesa. Inspirado nos *dashboards* icônicos da era de ouro dos videogames (como a interface do Xbox 360 e do PS3), ele oferece um ambiente focado 100% na estética e na praticidade. 

Construído com tecnologias web e um motor nativo de alta performance, o NebulaX não é apenas um organizador de pastas — é uma experiência imersiva feita para o "Couch Gaming" (jogar do sofá, usando apenas o controle).

---

## 📸 Prévia da Interface (Screenshots)

*(Nota: O design utiliza o conceito de Glassmorphism com um tema espacial para garantir que o foco seja sempre as artes dos seus jogos.)*

### Modo Carrossel
![Modo Carrossel do NebulaX](https://github.com/lerdo01/NebulaX/blob/614c0122f8583bf3b26290e9ef1b9f2bfe049ae2/screenshots/carousel_mode.png)
*Navegação fluida com reflexos dinâmicos e destaque automático para o título selecionado.*

### Modo Grade
![Modo Grade do NebulaX](https://github.com/lerdo01/NebulaX/blob/8c2d16829c551f79d1e272606a72b03a36139219/screenshots/grid_mode.jpg)
*Visualização expandida (5x3) com zoom dinâmico e organização por plataforma.*

### Setup e Configurações
![Configurações do NebulaX](https://github.com/lerdo01/NebulaX/blob/8c2d16829c551f79d1e272606a72b03a36139219/screenshots/config.png)
*Sistema de usuário para armazenar saves entre cada perfil.*

---

## ✨ O que esperar do lançamento?

O NebulaX chegará focado na estabilidade e na imersão, trazendo os seguintes recursos nativos:

*   **100% Plug & Play com Gamepads:** Controle toda a interface, troque de visualização e inicie os jogos usando controles de Xbox, PlayStation ou genéricos.
*   **Capas Automáticas (Powered by IGDB):** O sistema varre seus arquivos, identifica os jogos e faz o download automático de capas em alta resolução diretamente da API oficial do IGDB.
*   **Biblioteca Organizada (Deduplicação):** O backend foi programado para entender as nuances da emulação. Ele oculta arquivos redundantes (como `.bin` quando um `.cue` está presente) e mantém sua grade visual limpa.
*   **Múltiplos Usuários:** Crie até 5 perfis locais. Cada jogador pode ter seu próprio idioma (PT-BR, EN-US, ES-ES, JA-JP) e preferências visuais salvas independentemente.
*   **Áudio Imersivo:** Navegação tátil com efeitos sonoros integrados que respondem aos seus comandos no controle.

---

## 🛠️ Nos Bastidores (Tecnologia)

Para desenvolvedores e entusiastas de performance, o NebulaX foi construído para ser extremamente leve, apesar dos efeitos visuais avançados. A arquitetura divide-se em:

*   **Frontend:** React 19 + TypeScript + Custom CSS (Animações nativas e View Transitions).
*   **Backend/Engine:** Rust (Garantindo acesso rápido ao sistema de arquivos e manipulação de processos).
*   **Framework Desktop:** Tauri 2 (Consumo de RAM mínimo comparado a alternativas baseadas em Chromium padrão).

---

*Fique de olho. A decolagem do NebulaX acontece no dia **17 de Setembro**!*
